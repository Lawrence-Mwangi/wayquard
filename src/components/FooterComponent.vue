<script setup></script>

<template>
    <div class="footer_container">
        <div class="footer_infor">
            <img src="../assets/images/vr.jpg" width="40px" height="40px" alt="Logo">
            <p>WayQuad VR</p>
            <p>WaynePlaza, 2nd floor, room 25</p>
            <p>Kiambu,Kenya</p>
        </div>
        <div class="footer_links">
            <h2>Links</h2>
            <li><router-link :to="{ name:'home' }">Home</router-link></li>
            <li><router-link :to="{ name:'about' }">About</router-link></li>
            <li><router-link :to="{ name:'service' }">Service</router-link></li>
        </div>
        <div class="footer_media">
            <h2>Social Media Channel</h2>
            <a href="#" target="_blank">
                <img src="../assets/images/instagram.png" alt="instagram icon">
            </a>
            <a href="#" target="_blank">
                <img src="../assets/images/twitter.png" alt="twitter icon">
            </a>
            <a href="#" target="_blank">
                <img src="../assets/images/facebook.png" alt="facebook icon">
            </a>
            <a href="https://wa.me/254715138424?text='wayquad VR'">
                <img src="../assets/images/whatsapp.png" alt="whatapp icon">
            </a>
        </div>
    </div>
    <hr>
    <div class="footer_copyrigth">
        <p>&copy;2024 | WayQuad VR | All Rigth Reserved</p>
    </div>
</template>