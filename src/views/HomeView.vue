<script setup>
import Navbar from '@/components/NavbarComponent.vue'
import Hero from '@/views/HeroView.vue'
import Content  from '@/views/ContentView.vue'
import Contact from '@/views/ContactView.vue'
import Footer from '@/components/FooterComponent.vue'
</script>

<template>
    <Navbar/>

    <div class="hero" id="Hero">
        <Hero/>
    </div>

    <div class="main_container" id="Content">
        <Content/>
    </div>
    
    <div class="main_container" id="Contact">
        <Contact/>
    </div>

    <Footer/>
</template>
