<template>
    <button v-on:click="handleClick">Click</button>
</template>

<script setup>
    // import { defineEmits } from 'vue'

    const emit = defineEmits(['clicked']);

    const handleClick = () => {
        emit('clicked', 'data');
    }

</script>