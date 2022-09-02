<template>
    <div v-for="todo in todos" :key="todo.id">
        {{ todo.title }}
    </div>
</template>

<script setup>

    import axios from 'axios'

    let response = await axios.get('https://jsonplaceholder.typicode.com/todos')
    const todos = response.data

</script>