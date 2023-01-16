<template>
    <section class="homes">
        <Home name="Beautiful Family House" location="USA" :rooms="5" :area="300" :price="1200000" image="house-1.jpeg"/>
        <Home name="Modern Glass Villa" location="Estonia" :rooms="7" :area="450" :price="1700000" image="house-2.jpeg"/>
        <Home name="Cozy Country House" location="UK" :rooms="4" :area="250" :price="850000" image="house-3.jpeg"/>
        <Home name="Large Rustical Villa" location="Portugal" :rooms="6" :area="480" :price="1950000" image="house-4.jpeg"/>
        <Home name="Majestic Palace House" location="Germany" :rooms="18" :area="4230" :price="4000000" image="house-5.jpeg"/>
        <Home name="Modern Family Apartment" location="Italy" :rooms="3" :area="140" :price="2500000" image="house-6.jpeg"/>
    </section>
</template>
<script lang="ts">

import HomeCardVue from '@/components/layout/homes/HomeCard.vue';
export default {
    name: "Homes-component",
    components: {
        Home: HomeCardVue
    }
}
</script>