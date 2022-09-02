<template>
  <Emit v-on:clicked="handleClick" />
</template>

<script setup>
   import Emit from './components/Emit.vue'

   const handleClick = (e) => {
      console.log(e);
   }
</script>
