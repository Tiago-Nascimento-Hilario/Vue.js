<!-- Diretiva v-model -->

<!-- script -->
<script setup>
// Import ref para tornar reativo
import { ref } from 'vue';

    const texto = ref('');
</script>

<!-- html -->
<template>
    <input type="text" v-model="texto">
    <p>{{ texto }}</p>
</template>