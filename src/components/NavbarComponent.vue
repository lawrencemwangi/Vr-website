<script setup></script>contact

<template>
    <div class="nav_container">
        <div class="logo">
            <div class="image">
                <img src="../assets/images/vr.jpg" width="35px" height="35px" alt="logo image">
            </div>
            <router-link :to=" { name:'home'}">
                <h2>Wayne VR</h2>
            </router-link>
        </div>
        <div class="nav_links">
            <ul>
                <li><router-link :to="{ name:'home' }" >Home</router-link></li>
                <li><router-link :to="{ name:'about'}">About</router-link></li>
                <li><router-link :to="{ name:'service'}">service</router-link></li>
                <li> <a href="#Contact">Contact</a></li> 
            </ul>     
        </div>
     
    </div>
</template>