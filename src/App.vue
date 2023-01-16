<template>
  <div class="container">
    <Sidebar />
    <Header />
    <Realtors />
    <Features />
    <Story />
    <Homes />
    <Gallery />
    <Footer />
  </div>
</template>
<script setup lang="ts">
import Sidebar from './components/ui/Sidebar.vue';
import Header from './components/ui/Header.vue';
import Realtors from './components/layout/Realtors.vue';
import Features from './components/layout/Features.vue';
import Story from './components/layout/Story.vue';
import Homes from './components/layout/Homes.vue';
import Gallery from './components/layout/Gallery.vue';
import Footer from './components/ui/Footer.vue';

</script>

<style scoped>
</style>
