<template>
    {{ plural('cat', 5, true) }}
</template>

<script setup>
    import { meow as greeting } from './helper'
    import pluralize from 'pluralize'
    const plural = pluralize

</script>
