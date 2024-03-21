<script setup>
import Nav from '@/components/NavbarComponent.vue'
import Footer from '@/components/FooterComponent.vue'
</script>


<template>
    <Nav/>

    <div class="global_container">
        <h1>About Us</h1>

        <div class="about_container">
            <div class="about_content">
                <div class="about_items">
                    <p>Founded in 2022 by visionary technologists, Wayne VR embarked on a mission to redefine virtual reality experiences. Starting as a passion project,
                        it swiftly evolved into a premier destination for immersive VR content. Over the years, Wayne VR has pioneered groundbreaking advancements in VR technology, 
                        consistently pushing boundaries and setting new standards. With a commitment to innovation and quality, Wayne VR has garnered a reputation for delivering unparalleled
                        experiences that captivate users worldwide. From interactive simulations to captivating games and educational content, Wayne VR continues to inspire and delight, shaping the future
                        of entertainment and education. With a diverse portfolio and a dedication to excellence, Wayne VR remains at the forefront of the VR industry, leading the way into new realms of
                        possibility and imagination.
                    </p>
                </div>
                <div class="about_image">
                    <img src="../assets/images/vr.jpg" alt="about Image">
                </div>
            </div>
            <div class="founder">
                <h2>Our Founder</h2>
                <p>Wayne pioneers immersive VR experiences, revolutionizing entertainment and education with cutting-edge technology. 
                    Explore new realms, learn, and be entertained like never before, all within the virtual world crafted by Wayne.
                </p>
                <div class="founder_image">
                    <img src="../assets/images/wanye.jpeg" alt="wayne Image">
                    <div class="infor">
                        <p>Founder & CEO (WayQuad VR)</p>
                        <p>Wayne Orende</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <Footer/>
</template>

