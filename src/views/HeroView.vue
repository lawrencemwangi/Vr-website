<script setup></script>

<template>
    <div class="hero_container">
        <div class="hero_content">
            <h1>Discover the Magic of Virtual Experiences</h1>
            <p>Where Every Dream Becomes Your Reality</p>

            <div class="btn">
                <button><router-link :to="{ name: 'service' }">Our Serives</router-link></button>
                <button> <router-link :to="{ name:'about' }">Explore More</router-link></button>
            </div>
        </div>
    </div>
</template>