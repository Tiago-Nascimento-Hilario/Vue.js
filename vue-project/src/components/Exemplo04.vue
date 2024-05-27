<!-- Diretiva para criar estrutura html -->

<!-- script -->
<script setup>
    const tagP = '<p style="color:red">Gerado tag p com a diretiva v-html</p>'
</script>

<!-- html -->
<template>
    <p v-html="tagP"></p>
</template>