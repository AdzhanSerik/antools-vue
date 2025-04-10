<template>
    <div class="text-slate-200">
        <a href="#">{{ nav }}</a>
    </div>
</template>

<script setup>
defineProps({
    nav: String
})
</script>