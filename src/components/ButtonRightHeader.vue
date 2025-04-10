<template>
    <button :class="`bg-[${backgroundColor}]`">Hello</button>
</template>

<script setup>
defineProps({
    backgroundColor: String
})

</script>

<style lang="scss" scoped></style>