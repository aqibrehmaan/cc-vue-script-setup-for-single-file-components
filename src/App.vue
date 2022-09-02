<template>
    {{ authenticated }}
    <button v-on:click="meow">Meow</button>
</template>

<script setup>
  import { ref } from 'vue';

  const authenticated = ref(false);
  const meow = () => {
     authenticated.value = true;
  }

</script>
