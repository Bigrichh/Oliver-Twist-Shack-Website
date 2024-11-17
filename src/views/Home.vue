<template>

    <main class="w-full h-fit font-rhd bg-[#FFF4E6]">

        <!-- Hero Section -->
        <section class="hero w-full h-screen flex flex-col">
            <NavBar></NavBar>
            <div class=" w-full h-full text-white p-[24px] md:p-[48px] flex flex-col justify-end">
                <div data-aos="fade-up" data-aos-duration="1500">
                    <h1 class="font-light text-[32px] md:text-[40px] xl:text-[71px] 2xl:text-[85.35px] opacity-90">
                        WELCOME TO OLIVER
                        TWIST SHACK</h1>
                    <p class="font-light text-[18px] md:text-[20px] 2xl:text-[24px] opacity-80">Get ready to satisfy
                        your cravings with
                        bold flavors
                        and unforgettable bites. Oliver Twist Shack
                        is
                        here to wet your appetite with a fresh twist on your favorite comfort foods. We're serving up
                        delicious
                        meals
                        that keep you coming back for more.</p>
                </div>

            </div>
        </section>

        <!-- About Us -->
        <section class="w-full h-fit px-[24px] md:px-[48px] py-[48px] md:py-[96px]">
            <div class="flex flex-col xl:flex-row gap-[24px] xl:gap-0 xl:justify-between">

                <h2 data-aos="fade-up" data-aos-duration="1500" class="text-[24px] md:text-[32px] 2xl:text-[40px] font-light">About Us</h2>

                <div class="w-full xl:w-[870px] 2xl:w-[970px] opacity-50 flex flex-col gap-[48px]">
                    <p data-aos="fade-up" data-aos-duration="1500" class="text-[18px] md:text-[20px] 2xl:text-[24px] font-light">Oliver Twist Shack is where flavor
                        meets
                        sustainability. Our
                        passion is serving up delicious,
                        fresh dishes with a creative twist, all while staying committed to environmentally conscious
                        practices. Every meal is carefully crafted with ingredients that are both high-quality and
                        eco-friendly. Whether you’re enjoying one of our signature dishes or something from our
                        plant-based menu, you can feel good knowing that your choice supports our mission to minimize
                        waste and leave a lighter footprint on the planet.</p>
                    <div class="flex flex-col md:flex-row gap-[48px] text-[16px] md:text-[18px] font-light">
                        <p data-aos="fade-up" data-aos-duration="1500" >At Oliver Twist Shack, our mission is simple: to bring people
                            together through delicious
                            food, vibrant flavors, and an experience that feels like home. We’re committed to creating
                            meals that not only satisfy but also leave a lasting impression, using fresh,
                            locally-sourced ingredients and a touch of creativity in every dish. For us, it's all about
                            delivering great taste, quality, and warmth—every time.</p>
                        <p data-aos="fade-up" data-aos-duration="1500">
                            What makes Oliver Twist Shack stand out is our unique approach to combining the familiar
                            comfort of traditional dishes with exciting, bold flavors. While many restaurants stick to
                            the classics, we’re always pushing the boundaries, adding our twist to each meal and
                            delivering an experience that’s both fresh and nostalgic.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Popular Dishes -->
        <section class="w-full h-fit flex flex-col gap-[48px] py-[48px] md:py-[96px]">
            <div class="flex flex-col xl:flex-row md:gap-[24px] xl:gap-0 xl:justify-between px-[24px] md:px-[48px]">

                <h2 data-aos="fade-up" data-aos-duration="1500" class="text-[24px] md:text-[32px] 2xl:text-[40px] font-light">Popular Dishes</h2>

                <div class="w-full xl:w-[870px] 2xl:w-[970px] opacity-50">
                    <p data-aos="fade-up" data-aos-duration="1500" class="text-[18px] md:text-[20px] 2xl:text-[24px] font-light">Discover the creme de la creme of
                        menu delights
                        that our customers
                        can’t resist. Our popular picks feature the most sought after items from our menu, carefully
                        chosen for their exceptional quality and taste. Explore these favorites. </p>
                </div>
            </div>

            <div class="w-full flex flex-col gap-[24px]">
                <Vue3Marquee style="width: 100%;" :vertical="false" :pause-on-hover="false" :clone="false"
                    :duration="30">
                    <div class="w-full h-[400px] 2xl:h-[460px] flex gap-[24px] mr-[24px]">
                        <div class="w-[480px] xl:w-[530px] h-full imgoverlay">
                            <img class="w-full h-full object-cover" src="../assets/Homepage/PopularDishes/dish1.jpg"
                                alt="">
                        </div>
                        <div class="w-[480px] xl:w-[530px] h-full imgoverlay">
                            <img class="w-full h-full object-cover" src="../assets/Homepage/PopularDishes/dish2.jpg"
                                alt="">
                        </div>
                        <div class="w-[480px] xl:w-[530px] h-full imgoverlay">
                            <img class="w-full h-full object-cover" src="../assets/Homepage/PopularDishes/dish3.jpg"
                                alt="">
                        </div>
                        <div class="w-[480px] xl:w-[530px] h-full imgoverlay">
                            <img class="w-full h-full object-cover" src="../assets/Homepage/PopularDishes/dish4.jpg"
                                alt="">
                        </div>
                    </div>
                </Vue3Marquee>

                <Vue3Marquee style="width: 100%;" :vertical="false" :pause-on-hover="false" :clone="false"
                    :duration="30" :direction="'reverse'">
                    <div class="w-full h-[400px] 2xl:h-[460px] flex gap-[24px] mr-[24px]">
                        <div class="w-[480px] xl:w-[530px] h-full imgoverlay">
                            <img class="w-full h-full object-cover" src="../assets/Homepage/PopularDishes/dish5.jpg"
                                alt="">
                        </div>
                        <div class="w-[480px] xl:w-[530px] h-full imgoverlay">
                            <img class="w-full h-full object-cover" src="../assets/Homepage/PopularDishes/dish4.jpg"
                                alt="">
                        </div>
                        <div class="w-[480px] xl:w-[530px] h-full imgoverlay">
                            <img class="w-full h-full object-cover" src="../assets/Homepage/PopularDishes/dish6.jpg"
                                alt="">
                        </div>
                        <div class="w-[480px] xl:w-[530px] h-full imgoverlay">
                            <img class="w-full h-full object-cover" src="../assets/Homepage/PopularDishes/dish1.jpg"
                                alt="">
                        </div>
                    </div>
                </Vue3Marquee>
            </div>
        </section>

        <!-- Reviews -->
        <section
            class="w-full h-fit flex flex-col gap-[24px] xl:gap-[48px] px-[24px] md:px-[48px] py-[48px] md:py-[96px]">
            <h2 data-aos="fade-up" data-aos-duration="1500" class="text-[24px] md:text-[32px] 2xl:text-[40px] font-light">Reviews</h2>
            <div data-aos="fade-up" data-aos-duration="1500" class="w-full flex flex-wrap gap-[24px]">
                <div  v-for="review in reviews"
                    class="w-full md:w-[48%] xl:w-[31.8%] 2xl:w-[458px] flex flex-col gap-[16px] p-[24px] text-[16px] md:text-[18px] border-solid border-[1px] border-black border-opacity-5">
                    <p class="opacity-50">{{ review.review }}</p>
                    <div class="flex gap-[16px]">
                        <div class="w-[40px] md:w-[50px] h-[40px] md:h-[50px] bg-black rounded-full">
                            <img :src="review.image" alt="Image Of Reviewer">
                        </div>
                        <div>
                            <p class="font-medium">{{ review.reviewerName }}</p>
                            <p class="opacity-50">Review From Google</p>
                        </div>
                    </div>
                </div>

            </div>
        </section>

        <!-- Upcoming Events -->
        <section class="w-full h-fit flex flex-col gap-[48px] px-[24px] md:px-[48px] py-[48px] md:py-[96px]">
            <h2 data-aos="fade-up" data-aos-duration="1500" class="text-[24px] md:text-[32px] 2xl:text-[40px] font-light">Upcoming Events At The Shack</h2>
            <div data-aos="fade-up" data-aos-duration="1500" class="w-full flex flex-wrap gap-[24px]">
                <div v-for="event in events"
                    class="w-full md:w-[48%] xl:w-[31.8%] 2xl:w-[23.5%] flex flex-col gap-[16px] text-[18px] border-solid border-[1px] border-black border-opacity-5">
                    <div class="w-full h-[380px] md:h-[400px] 2xl:h-[430px]">
                        <img class="w-full h-full object-cover" :src="event.banner" alt="Event Banner">
                    </div>
                    <div class="flex flex-col gap-[4px] px-[24px] pb-[24px]">
                        <p class="font-medium">{{ event.eventName }}</p>
                        <div>
                            <p class="opacity-50">{{ event.eventDate }}</p>
                            <p class="opacity-50">{{ event.eventTime }}</p>
                        </div>
                    </div>
                </div>

            </div>
        </section>

        <!-- Green Twist Initiative -->
        <section class="w-full h-fit flex flex-col gap-[48px] py-[96px]">
            <Vue3Marquee style="width: 100%;" :vertical="false" :pause-on-hover="false" :clone="false" :duration="30">
                <div class="w-full h-[370px] xl:h-[470px] flex gap-[24px] mr-[24px]">
                    <div v-for="image in gtiimages.slice(0, 3)" class="w-[380px] xl:w-[530px] h-full imgoverlay">
                        <img class="w-full h-full object-cover" :src="image" alt="">
                    </div>
                </div>
            </Vue3Marquee>

            <div class="flex flex-col gap-[10px] px-[24px] md:px-[48px] ">
                <h2 class="text-[24px] md:text-[32px] 2xl:text-[40px] font-light">Support the Green Twist Initiative
                </h2>
                <p class="text-[18px] md:text-[20px] 2xl:text-[24px] font-light">Bring back your paper bag in good
                    condition with your
                    next purchase
                    and unlock a 10% discount on your
                    next meal! Together, we can take a bold step toward reducing waste and protecting the environment,
                    one meal at a time.</p>
            </div>
            <Vue3Marquee style="width: 100%;" :vertical="false" :pause-on-hover="false" :clone="false" :duration="30"
                :direction="'reverse'">
                <div class="w-full h-[370px] xl:h-[470px] flex gap-[24px] mr-[24px]">
                    <div v-for="image in gtiimages.slice(3)" class="w-[380px] xl:w-[530px] h-full imgoverlay">
                        <img class="w-full h-full object-cover" :src="image" alt="">
                    </div>
                </div>
            </Vue3Marquee>

        </section>

        <!-- Banner Image -->
        <section
            class="w-full h-screen 2xl:h-[110vh] relative before:content-[''] before:w-full before:h-full before:absolute before:bg-black before:bg-opacity-5">
            <img class="w-full h-full object-cover" src="../assets/Homepage/PopularDishes/dish2.jpg" alt="Banner Image">
        </section>

        <!-- FAQs -->
        <section class=" w-full h-fit flex flex-col gap-[48px] px-[24px] md:px-[48px] py-[48px] md:py-[96px]">
            <h2 data-aos="fade-up" data-aos-duration="1500" class="text-[24px] md:text-[32px] 2xl:text-[40px] font-light">Frequently Asked Questions</h2>
            <div data-aos="fade-up" data-aos-duration="1500" class="p-[10px] flex flex-col gap-[10px]">
                <div v-for="(faq, index) in FAQs"
                    class="w-full flex flex-col md:flex-row gap-[24px] md:gap-[64px] py-[32px] border-t-[1px] border-b-[1px] border-black border-opacity-10">
                    <p class="w-full text-[20px] 2xl:text-[24px] font-light">{{ index + 1 }}. {{ faq.question }}</p>
                    <p class="w-full text-[18px] font-light opacity-50">{{ faq.answer }}</p>
                </div>
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
import { Vue3Marquee } from 'vue3-marquee';
import AOS from 'aos';
import 'aos/dist/aos.css';

export default {
    name: 'Home',
    components: {
        NavBar,
        Vue3Marquee
    },
    data() {
        return {
            reviews: [
                {
                    review: 'I appreciate the customer service you get both over the phone and In person. They also have delicious food that keeps me coming back. I have to say I really like the new place - they’ve definitely stepped their game up. There’s no place within that area that matches up ❤️',
                    reviewerName: 'Sankines',
                    image: new URL('../assets/Homepage/Reviewerimages/6.png', import.meta.url).href
                },
                {
                    review: 'Went there with friends and I absolutely enjoyed the place. Yummy food, lovely music and oh, met some celebrities that day🤭',
                    reviewerName: 'Clara Bismarck',
                    image: new URL('../assets/Homepage/Reviewerimages/2.png', import.meta.url).href,

                },
                {
                    review: 'Fun fun fun!!! Nicely arranged setting with great lighting, delicious meals and OMG the DJ is on FIRE! Great place for friends to hangout. I enjoyed every bit of time spent there. I\'m surely coming back again and again.',
                    reviewerName: 'Naana',
                    image: new URL('../assets/Homepage/Reviewerimages/3.png', import.meta.url).href
                },
                {
                    review: 'Great new setup. Nice place to unwind with friends or colleagues after work. Food is moderately expensive.',
                    reviewerName: 'Jeffery Akoto-Domey',
                    image: new URL('../assets/Homepage/Reviewerimages/4.png', import.meta.url).href
                },
                {
                    review: 'Such a freaking vibe! Great drinks and food is incredible and affordable. Cant wait to go back!',
                    reviewerName: 'Vesta Adofo',
                    image: new URL('../assets/Homepage/Reviewerimages/5.png', import.meta.url).href,
                },
                {
                    review: 'All the good reviews about this place are actually true; whaaat! Food is great and affordable plus waitresses are on top of their game...I\'m definitely going back there again.I\'m surely asking for more soon',
                    reviewerName: 'Muhammed Muftao Dakpo',
                    image: new URL('../assets/Homepage/Reviewerimages/1.png', import.meta.url).href,
                },
            ],
            events: [
                {
                    eventName: 'Sa Nkwan(The Fufu Party) 4th Edition',
                    eventDate: 'Saturday 5th October 2024',
                    eventTime: '11am Till Late',
                    banner: new URL('../assets/Events/event1.png', import.meta.url).href,
                },
                {
                    eventName: 'Puff sip & paint',
                    eventDate: 'Saturday 28th September 2024',
                    eventTime: '5pm Till Late',
                    banner: new URL('../assets/Events/event2.png', import.meta.url).href,
                },
                {
                    eventName: 'Kick Off Fridays Karaoke ',
                    eventDate: 'Every Friday',
                    eventTime: '8pm',
                    banner: new URL('../assets/Events/event3.png', import.meta.url).href,
                },
                {
                    eventName: 'Kizomba Day Party',
                    eventDate: 'Sunday 29th September 2024',
                    eventTime: '2pm',
                    banner: new URL('../assets/Events/event4.png', import.meta.url).href,
                },
            ],
            gtiimages: [
                new URL('../assets/Homepage/GTI/gti1.jpg', import.meta.url).href,
                new URL('../assets/Homepage/GTI/gti2.jpg', import.meta.url).href,
                new URL('../assets/Homepage/GTI/gti3.jpg', import.meta.url).href,
                new URL('../assets/Homepage/GTI/gti4.jpg', import.meta.url).href,
                new URL('../assets/Homepage/GTI/gti5.jpg', import.meta.url).href,
                new URL('../assets/Homepage/GTI/gti6.jpg', import.meta.url).href,
            ],
            FAQs: [
                {
                    question: 'What type of cuisine does Oliver Twist Shack offer?',
                    answer: 'At Oliver Twist Shack, we offer a fusion of global flavors with a modern twist on classic comfort foods. Our menu features a variety of dishes inspired by different culinary traditions, ensuring there\'s something for everyone to enjoy.',
                },
                {
                    question: 'Do you accommodate dietary restrictions or allergies?',
                    answer: 'Yes! We offer options for a variety of dietary needs, including vegetarian, vegan, and gluten-free choices. If you have specific allergies, please let our staff know, and we\'ll do our best to accommodate your request.',
                },
                {
                    question: 'Can I make a reservation?',
                    answer: 'Absolutely! You can make reservations directly on our website or by giving us a call. Walk-ins are also welcome, but reservations are recommended during peak hours to ensure you get a table.',
                },
                {
                    question: 'Do you offer delivery or takeout services?',
                    answer: 'Yes, we offer both delivery and takeout. You can place an order through our website or via third-party delivery platforms like Uber Eats or DoorDash. We also provide a convenient takeout option for those who prefer to pick up their meals.',
                },
                {
                    question: 'What is the Green Twist Initiative?',
                    answer: 'The Green Twist Initiative is our commitment to sustainability. We focus on reducing waste and recycling. Bring back your paper bag in good condition with your next purchase and unlock a 10% discount on your next meal! ',
                },
                {
                    question: 'Do you host private events or catering services?',
                    answer: 'Yes, we offer both! Whether you\'re planning a small gathering or a large celebration, we can accommodate private events.We also offer catering for off - site events.Contact us for more details on packages and availability.',
                },
            ]
        }
    },
    mounted() {
        AOS.init();
    },
}
</script>

<style scoped>
.hero {
    background-image: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('../assets/Homepage/herosectionimg.jpg');
    background-size: cover;
    background-position: center;
}

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
    background-color: rgba(0, 0, 0, 0.05);
    z-index: 1;
}
</style>
