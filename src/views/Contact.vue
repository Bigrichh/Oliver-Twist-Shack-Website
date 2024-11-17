<template>

    <main class="w-full h-fit font-rhd bg-[#FFF4E6]">

        <!-- Hero Section -->
        <section class="hero w-full h-fit xl:h-screen flex flex-col">
            <NavBar></NavBar>
            <div class="relative w-full h-[65%] px-[24px] md:px-[48px]">
                <div class="imgoverlay h-full">
                    <img data-aos="fade-up" data-aos-duration="500" class="w-full h-full object-cover"
                        src="../assets/Homepage/herosectionimg.jpg" alt="Food menu">
                    <h1 data-aos="fade-up" data-aos-duration="500"
                        class="z-10 absolute bottom-[32px] left-[32px] text-white font-light text-[32px] md:text-[40px] xl:text-[71px] 2xl:text-[85.35px]">
                        GET IN TOUCH</h1>
                </div>
            </div>

            <div class="w-full flex flex-col xl:flex-row gap-[24px] justify-between py-[24px] md:py-[48px] xl:py-[24px] px-[24px] md:px-[48px]">
                <div class="flex flex-col gap-[8px]">
                    <h2 class="text-[24px] md:text-[32px] font-light">Opening Hours</h2>
                    <div class="text-[18px] font-light">
                        <p>Monday - Thursday <span class="font-medium">12pm -11:30pm</span> </p>
                        <p>Friday - Sunday <span class="font-medium">12pm -3am </span> </p>
                    </div>
                </div>
                <div class="flex flex-col gap-[8px]">
                    <h2 class="text-[24px] md:text-[32px] font-light">Find Us</h2>
                    <div class="text-[18px] font-light">
                        <p>Oliver Twist Shack, Eduardo Mohdlana Rd, Accra</p>
                    </div>
                </div>
                <div class="flex flex-col gap-[8px]">
                    <h2 class="text-[24px] md:text-[32px] font-light">Get In Touch</h2>
                    <div class="text-[18px] font-light">
                        <p>020 687 4225</p>
                    </div>
                </div>

                <div class="flex gap-[16px]">
                    <div class="bg-[#EF4C5D] w-fit h-fit p-[16px] flex items-center justify-center">
                        <Icon icon="mdi:instagram" class="text-[28px] 2xl:text-[32px]" style="color: white" />
                    </div>
                    <div class="bg-[#266305] w-fit h-fit p-[16px] flex items-center justify-center">
                        <Icon icon="ic:baseline-whatsapp" class="text-[28px] 2xl:text-[32px]" style="color: white" />
                    </div>
                    <div class="bg-[#000000] w-fit h-fit p-[16px] flex items-center justify-center">
                        <Icon icon="fa6-brands:x-twitter" class="text-[28px] 2xl:text-[32px]" style="color: white" />
                    </div>
                </div>

            </div>
        </section>
    </main>
</template>


<script>
import NavBar from '@/components/NavBar.vue';
import AOS from 'aos';
import 'aos/dist/aos.css';
import { Icon } from '@iconify/vue';

export default {
    name: 'Contact',
    components: {
        NavBar,
        Icon
    },
    mounted() {
        AOS.init();
    },
}
</script>

<style scoped>
.imgoverlay {
    position: relative;
}

.imgoverlay::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    z-index: 1;
}
</style>