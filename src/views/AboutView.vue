<script setup>
import Nav from '@/components/NavbarComponent.vue'
import Footer from '@/components/FooterComponent.vue'

</script>

<template>
    <Nav/>
    <div class="main_container">
        <h1>About Us</h1>
        <div class="about_container">
            <p>Founded in 2022 by visionary technologists, Wayne VR embarked on a mission to redefine virtual reality experiences. Starting as a passion project,
                it swiftly evolved into a premier destination for immersive VR content. Over the years, Wayne VR has pioneered groundbreaking advancements in VR technology, 
                consistently pushing boundaries and setting new standards. With a commitment to innovation and quality, Wayne VR has garnered a reputation for delivering unparalleled
                experiences that captivate users worldwide. From interactive simulations to captivating games and educational content, Wayne VR continues to inspire and delight, shaping 
                the future of entertainment and education. With a diverse portfolio and a dedication to excellence, Wayne VR remains at the forefront of the VR industry, leading the way into 
                new realms of possibility and imagination.
            </p>
            <div class="image">
                <img src="../assets/images/exprience.jpg" alt="vr Image">
            </div>
        </div>

        <div class="owner">
            <h1>Our Founder</h1>
            <p>Wayne is a  Pioneering immersive VR experiences, shaping the future of entertainment and education with groundbreaking technology.</p>
            
            <div class="owner_image">
                <img src="../assets/images/wayne.jpg" alt="wayne photo">
                <span>Founder Wayne VR</span>
                <p>Wayne Orende</p>

            </div>
        </div>
    </div>

    <Footer/>
</template>