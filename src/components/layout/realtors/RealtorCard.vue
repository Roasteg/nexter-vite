<template>
    <img :src="'src/assets/img/' + $props.image" alt="Realtor" class="realtors__img">
            <div class="realtros__details">
                <h4 class="heading-4 heading-4--light">{{ $props.name }}</h4>
                <p class="realtors__sold">{{ $props.sold }} houses sold</p>
            </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
  name: "Realtor-card",
  props: {
    name: String,
    sold: Number,
    image: String
  },
})
</script>