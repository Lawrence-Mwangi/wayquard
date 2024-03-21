<script setup>
import Nav from '@/components/NavbarComponent.vue'
import Hero from '@/views/HeroView.vue'
import Content from '@/views/ContentView.vue'
import Games from '@/views/GamesView.vue'
import Contact from '@/views/ContactView.vue'
import Footer from '@/components/FooterComponent.vue'
</script>

<template>
    <Nav/>

    <section class="hero">
        <Hero/>
    </section>

    <section class="global_container" id="Content">
        <Content/>
    </section>

    <section class="global_container" id="Games">
        <Games/>
    </section>

    <section class="global_container" id="Contact">
        <Contact/>
    </section>

    <Footer/>

</template>
