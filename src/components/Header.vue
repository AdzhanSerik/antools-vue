<template>
    <div>
        <div class="logo text-white">
            <img src="../assets/logo.svg" alt="">
            <span>antools.</span>
        </div>
        <nav>
            <Navigation v-for="(nav, index) in navigation" :key="index" :nav="nav" />
        </nav>
        <div>
            <ButtonRightHeader backgroundColor="#FF6E30" />
            <ButtonRightHeader backgroundColor="#FFF" />
        </div>

    </div>
</template>

<script setup>

defineProps({
    navigation: Array,
})
import Navigation from "./Navigation.vue";
import ButtonRightHeader from "./ButtonRightHeader.vue";

</script>
