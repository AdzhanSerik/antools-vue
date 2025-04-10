<template>
    <button :class="backgroundColor">{{ textButton }}</button>
</template>

<script setup>
defineProps({
    backgroundColor: String,
    textButton: String
})

</script>

<style lang="scss" scoped></style>