<template>
   <suspense>
      <template #default>
          <Todos />
      </template>

      <template #fallback>
          Loading...
      </template>

   </suspense>
</template>

<script setup>
    import Todos from './components/Todos.vue'
</script>
