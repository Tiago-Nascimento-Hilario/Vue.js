<!-- Diretiva v-class -->



<!-- script -->
<script setup>
    const validacao = true;
</script>

<!-- css -->

<style>
    .verdadeira{
        background-color: green;
    }
    .falsa{
        background-color: red;
    }

</style>

<!-- html -->
<template>
    <p :class="validacao ? 'verdadeira' : 'falsa'" >Aplicando a diretiva class</p>
</template>