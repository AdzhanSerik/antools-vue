<template>
    <button class="px-4 py-2 rounded-[5px]" :class="backgroundColor">{{ textButton }}</button>
</template>

<script setup>
defineProps({
    backgroundColor: String,
    textButton: String
})

</script>

<style lang="scss" scoped></style>