<template>
    <header class="header">
        <img src="@/assets/img/logo.png" alt="Nexter logo" class="header__logo">
        <h3 class="heading-3">Your own home:</h3>
        <h1 class="heading-1">The ultimate personal freedom</h1>
        <button class="btn header__btn">View our properties</button>
        <div class="header__seenon-text">Seen on</div>
        <div class="header__seenon-logos">
            <img src="@/assets/img/logo-bbc.png" alt="Seen on logo 1">
            <img src="@/assets/img/logo-forbes.png" alt="Seen on logo 2">
            <img src="@/assets/img/logo-techcrunch.png" alt="Seen on logo 3">
            <img src="@/assets/img/logo-bi.png" alt="Seen on logo 4">
        </div>
    </header>
</template>
<script lang="ts">
export default {
    name: "Header-component"
}
</script>