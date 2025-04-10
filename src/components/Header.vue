<template>
    <div>
        <div class="logo text-white">
            <img src="../assets/logo.svg" alt="">
            <span>antools.</span>
        </div>
        <nav>
            <Navigation v-for="(nav, index) in navigation" :key="index" :nav="nav" />
        </nav>

    </div>
</template>

<script setup>
defineProps({
    navigation: Array,
})
import Navigation from "./Navigation.vue";

</script>

<style lang="scss" scoped></style>