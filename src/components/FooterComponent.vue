<script setup></script>

<template>
    <div class="footer_container">
        <div class="footer_content">
            <img src="../assets/images/vrheadset.jpg" width="50px" height="50px" alt="logo img">
            <p>Wayne VR</p>
            <p>Wayne Plaza, 2nd floor, Room 213</p>
            <span>Kiambu, Kenya</span>
        </div>

        <div class="footer_links">
            <h3>Links</h3>
            <li><router-link :to="{ name:'home' }" >Home</router-link></li>
            <li><router-link :to="{ name:'about'}">About</router-link></li>
            <li><router-link :to="{ name:'service'}">Services</router-link></li>
            <li><a href="#Contact">Contact</a></li>
        </div>

        <div class="social_media">
            <h4>Social Media</h4>
            <a href="#" target="_blank">
                <img src="../assets/images/instagram.png" alt="instagram icon">
            </a>
            <a href="#" target="_blank">
                <img src="../assets/images/twitter.png" alt="twitter icon">
            </a>
            <a href="#" target="_blank">
                <img src="../assets/images/facebook.png" alt="facebook icon">
            </a>
        </div>
    </div>
    <div class="footer_copyright">
        <p>&copy;2024 | Wayne Vertual Reality | All rights reserved</p>
    </div>
</template>