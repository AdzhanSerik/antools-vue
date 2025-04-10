<template>
    <button class="px-4 py-2 rounded-[5px] !font-bold" :class="backgroundColor + ' ' + textColor">
        {{ textButton }}
    </button>
</template>

<script setup>
defineProps({
    backgroundColor: String,
    textButton: String,
    textColor: String
})

</script>