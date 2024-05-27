<!-- Condicionais com diretivas -->

<!-- script -->
<script setup>
    let exibir = true;
    let nome = 'Tiago';
    let media = 8 ;
</script>

<!-- html -->
<template>
    <!-- diretiva de condição booleana -->
    <h1 v-if="exibir">ola!{{ nome }}</h1>
    <br>
    <p v-if="media >= 7">Aprovado</p>
    <p v-else-if="media >= 5 && media < 7">Em Recuperação</p>
    <p v-else>Reprovado</p>
    
</template>