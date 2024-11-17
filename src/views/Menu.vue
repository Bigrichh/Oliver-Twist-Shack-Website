<template>

    <main class="w-full h-fit font-rhd bg-[#FFF4E6]">

        <!-- Hero Section -->
        <section class="hero w-full h-fit flex flex-col">
            <NavBar></NavBar>
            <div class="w-full h-fit flex flex-col gap-[24px] md:gap-[48px] px-[24px] md:px-[48px] py-[24px] md:py-[48px]">
                <img data-aos="fade-up" data-aos-duration="1500" class="w-full h-fit object-fit" src="../assets/Menu/foodmenu.jpg" alt="Food menu">
                <img data-aos="fade-up" data-aos-duration="1500" class="w-full h-fit object-fit" src="../assets/Menu/drinkmenu.jpg" alt="Drink menu">
            </div>
        </section>

        <footer class="flex flex-col gap-[24px] pt-[12px] px-[24px] md:px-[120px] xl:px-[240px] pb-[48px] items-center">
            <h2 class="text-[32px] md:text-[48px] xl:text-[80px] 2xl:text-[100px] text-[#EA4808] font-light"> OLIVER
                <span class="text-[#047766]">TWIST</span> SHACK
            </h2>
            <div class="w-full flex flex-col gap-[48px] md:gap-0 md:flex-row justify-between">
                <div class="flex flex-col gap-[8px]">
                    <h3 class="text-[20px] 2xl:text-[24px]">About Us</h3>
                    <div class="flex flex-col gap-[8px] text-[18px] 2xl:text-[20px] opacity-40">
                        <p>Green Twist Inititative</p>
                        <p>Find Us</p>
                        <p>Menu</p>
                        <p>Meet Our Staff</p>
                    </div>
                </div>
                <div class="flex flex-col gap-[8px]">
                    <h3 class="text-[20px] 2xl:text-[24px]">Contact Details</h3>
                    <div class="flex flex-col gap-[8px] text-[18px] 2xl:text-[20px] opacity-40">
                        <p>+233 000 000 000</p>
                        <p>+233 000 000 000</p>
                        <p>email email email</p>
                    </div>
                </div>

                <div class="flex flex-col gap-[8px]">
                    <h3 class="text-[20px] 2xl:text-[24px]">Socials</h3>
                    <div class="flex flex-col gap-[8px] text-[18px] 2xl:text-[20px] opacity-40">
                        <p>Instagram</p>
                        <p>Twitter</p>
                        <p>Whatsapp</p>
                    </div>
                </div>
            </div>
        </footer>



    </main>
</template>


<script>
import NavBar from '@/components/NavBar.vue';
import AOS from 'aos';
import 'aos/dist/aos.css';

export default {
    name: 'Menu',
    components: {
        NavBar,
    },
    mounted() {
        AOS.init();
    },
}
</script>
