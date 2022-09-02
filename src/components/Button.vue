<template>
    <button>{{ title }}</button>
</template>

<script setup>
    // import { defineProps } from 'vue'

    // defineProps({
    //     title: String
    // });

    const props = defineProps({
        title: String
    });

    console.log(props.title)

</script>