<template>
    <div class="realtors">
        <h3 class="heading-3">Top 3 Realtors</h3>
        <div class="realtors__list">
            <Realtor name="Patrick Bateman" :sold="99" image="realtor-1.jpeg"/>
            <Realtor name="Ellen Page" :sold="81" image="realtor-2.jpeg"/>
            <Realtor name="Paul Allen" :sold="70" image="realtor-3.jpeg"/>
        </div>
    </div>
</template>

<script lang="ts">
import RealtorCardVue from './realtors/RealtorCard.vue';
export default { 
    name: "Realtors-component",
    components: {
        Realtor: RealtorCardVue
    }
}
</script>