<script setup>
import { ref } from 'vue';
import { useRouter } from 'vue-router';

const isResponsive = ref(false);
const router = useRouter();

const toggleMenu = () => {
  isResponsive.value = !isResponsive.value;
};

const navigate = (sectionId) => {
  if (sectionId === 'home' || sectionId === 'about' || sectionId === 'service' || sectionId ==='Contact') {
    router.push({ name: sectionId });
    isResponsive.value = false; 
  }
};

</script>

<template>
    <div class="nav_container">
        <div class="logo">
            <img src="../assets/images/vr.jpg" width="40px" height="40px" alt="Logo Image">
            <router-link :to="{ name:'home' }">Wayquad VR</router-link>
        </div>

        <div class="nav_links" :class="{ 'responsive': isResponsive }">
            <ul :class="{ 'show': isResponsive }">
                <li><router-link :to="{ name:'home' }" @click="navigate('home')">Home</router-link></li>
                <li><router-link :to="{ name:'about' }" @click="navigate('about')">About</router-link></li>
                <li><router-link :to="{ name:'service' }" @click="navigate('service')">Service</router-link></li>
                <li><a href="#Contact" @click="toggleMenu">Contact</a></li>
            </ul>
        </div>
        <div class="burger" @click="toggleMenu" :class="{ 'active': isResponsive }">
            <span></span>
            <span></span>
            <span></span>
        </div>
    </div>
</template>