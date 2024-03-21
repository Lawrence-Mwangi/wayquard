<script setup></script>

<template>
    <div class="hero_container">
        <div class="hero_content">
            <div class="hero_items">
                <h1>Discover the Magic of Virtual Experiences</h1>
                <span>Where Every Dream Becomes Your Reality</span>
                <p>Welcome to WayQuad VR, your gateway to immersive adventures! Dive into a world where reality blurs and dreams come to life.
                    With cutting-edge technology and a vast library of experiences, WayQuad VR takes you on unforgettable journeys
                </p>
                <div class="btn">
                    <button><router-link :to="{ name:'service' }">Our Service</router-link></button>
                    <button><router-link :to="{ name:'about' }">Explore More</router-link></button>
                </div>
            </div>
        </div>
    </div>
</template>