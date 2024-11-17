<template>
    <nav class="h-fit w-full flex flex-col">

        <div
            class="relative flex flex-row w-full h-fit justify-between font-rhd py-[16px] px-[24px] md:px-[48px] bg-black">
            <div>
                <p class="text-[20px] 2xl:text-[24px] text-[#EA4808] font-medium">
                    OLIVER
                    <span class="text-[#047766]">
                        TWIST
                    </span>
                    SHACK
                </p>
            </div>
            <div v-show="!mobile" class="flex flex-row gap-[40px] text-[18px] font-light text-white">
                <router-link :to="{ name: 'home' }">
                    <div>Home</div>
                </router-link>
                <router-link :to="{ name: 'about' }">
                    <div>About</div>
                </router-link>
                <router-link :to="{ name: 'menu' }">
                    <div>Menu</div>
                </router-link>
                <router-link :to="{ name: 'contact' }">
                    <div>Contact</div>
                </router-link>
            </div>

            <!-- Hamburger menu icon. Becomes visible when the screen reduces to tablet/mobile size - When clicked, it toggles a side navigation panel that slides in from the left -->
            <div class="flex items-center" v-show="mobile">
                <i @click="toggleMobileNav" class="fa-solid fa-bars" :class="{ 'icon-active': mobileNav }"></i>
            </div>
        </div>

        <transition name="mobile-nav">
            <div v-show="mobileNav"
                class="w-full h-full z-40 fixed top-0 left-0 bg-black flex flex-col items-center justify-center gap-[40px] text-[18px] font-light text-white">
                <router-link :to="{ name: 'home' }">
                    <div>Home</div>
                </router-link>
                <router-link :to="{ name: 'about' }">
                    <div>About</div>
                </router-link>
                <router-link :to="{ name: 'menu' }">
                    <div>Menu</div>
                </router-link>
                <router-link :to="{ name: 'contact' }">
                    <div>Contact</div>
                </router-link>
                <div @click="toggleMobileNav" class="hover:cursor-pointer">
                    <Icon icon="material-symbols:close" width="32" height="32" style="color: white" />
                </div>
            </div>
        </transition>
    </nav>


</template>

<script>
import { Icon } from '@iconify/vue';

export default {
    name: 'NavBar',
    components: {
        Icon,
    },
    data() {
        return {
            mobile: false,
            mobileNav: false,
            windowWidth: null,
        }
    },

    created() {
        window.addEventListener("resize", this.ckeckScreen);
        this.ckeckScreen();
    },

    methods: {
        toggleMobileNav() {
            this.mobileNav = !this.mobileNav
        },

        ckeckScreen() {
            this.windowWidth = window.innerWidth;
            if (this.windowWidth <= 1023) {
                this.mobile = true;
                return;
            } else {
                this.mobile = false;
                this.mobileNav = false;
                return;
            }
        },

        showCart() {
            this.$store.state.showCart = !this.$store.state.showCart
        },
    },

    watch: {
        $route() {
            this.mobileNav = false;  // Close mobile nav on route change
        },
    },

}
</script>


<style scoped>
.router-link-active {
    opacity: 1;
    font-weight: 500;
}

a {
    opacity: 0.5;
    text-decoration: none;
    color: white;
}

a:hover {
    opacity: 1
}

.icon-active {
    transform: rotate(180deg);
}

i {
    color: white;
    cursor: pointer;
    font-size: 22px;
    transition: 0.8s ease all;

    @media only screen and (max-width: 320px) {
        /* Your CSS rules for screens up to 320 pixels wide */
        font-size: 22px;
    }

}

.mobile-nav-enter-active,
.mobile-nav-leave-active {
    transition: 0.7s ease all;
}

.mobile-nav-enter-from,
.mobile-nav-leave-to {
    transform: translateX(-100%);
}

.mobile-nav-enter-to {
    transform: translateX(0);
}
</style>