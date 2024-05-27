<!-- Estrutura de repetição -->

<!-- script -->
<script setup>
    const estados = ['Rio de janeiro', 'São paulo', 'Santa catarina', 'Rio grande do sul']
</script>

<!-- html -->
<template>
    <ol>
        <li v-for="estado in estados ">{{ `Estado: ${estado}` }}</li>
    </ol>
</template>