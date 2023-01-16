<template>
    <div class="home">
            <img :src="'src/assets/img/' + $props.image" alt="House" class="home__img">
            <svg class="home__like">
                <use xlink:href="@/assets/svg/sprite.svg#icon-heart-full" /> 
            </svg>
            <h5 class="home__name">{{$props.name}}</h5>
            <div class="home__location">
                <svg>
                    <use xlink:href="@/assets/svg/sprite.svg#icon-map-pin" /> 
                </svg>
                <p>{{ $props.location }}</p>
            </div>
            <div class="home__rooms">
                <svg>
                    <use xlink:href="@/assets/svg/sprite.svg#icon-profile-male" /> 
                </svg>
                <p>{{ $props.rooms }} rooms</p>
            </div>
            <div class="home__area">
                <svg>
                    <use xlink:href="@/assets/svg/sprite.svg#icon-expand" /> 
                </svg>
                <p>{{ $props.area }} m<sup>2</sup></p>
            </div>
            <div class="home__price">
                <svg>
                    <use xlink:href="@/assets/svg/sprite.svg#icon-key" /> 
                </svg>
                <p>${{ $props.price }}</p>
            </div>
            <button class="btn home__btn">Contact realtor</button>
        </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
  name: "Home-card",
  props: {
    name: String,
    location: String,
    rooms: Number,
    area: Number,
    price: Number,
    image: String
  },
})
</script>