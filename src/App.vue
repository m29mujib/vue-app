<script setup>
import About from './components/About/About.vue';
import Home from './components/Home/Home.vue';
import Navbar from './components/Navbar/Navbar.vue';
import Iklan from './components/Iklan/Iklan.vue'
import Komunik from './components/Komunik/Komunik.vue'

</script>

<template>
  <div>
    <Navbar/>
    <About name="Search & Rent Apartment Easily" button="Read Started"/>
    <Iklan/>
    <Home/>
    <Komunik/>
  </div>
</template>



