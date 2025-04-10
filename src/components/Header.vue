<template>
    <div class="">
        <div class="flex items-center justify-between">
            <div class="logo text-white flex items-center gap-4">
                <img src="../assets/logo.svg" alt="">
                <span>antools.</span>
            </div>
            <nav class="flex items-center gap-[40px] ">
                <Navigation v-for="(nav, index) in navigation" :key="index" :nav="nav" />
            </nav>
            <div class="flex items-center gap-4">
                <ButtonRightHeader backgroundColor="" textColor="text-[#C4C4C4]" textButton="Login" />
                <ButtonRightHeader backgroundColor="bg-[#FF6E30]" textColor="text-white" textButton="SignUp" />
            </div>

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
