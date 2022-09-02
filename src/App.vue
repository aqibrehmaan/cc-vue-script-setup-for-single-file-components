<template>
    {{ pluralize('cat', count, true) }}
</template>

<script setup>
    import { ref } from 'vue'
    import pluralize from 'pluralize'

    const count = ref(2);

</script>
