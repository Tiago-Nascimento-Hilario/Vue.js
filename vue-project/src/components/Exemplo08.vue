<!-- Evento submit -->
<script setup>
    function cadastrar(event) {
        alert('Enviando formulário');
        
        // event.preventDefault();
        
    }
</script>

<template>
    <form action="https://www.google.com.br" @submit="cadastrar"  >
        <input type="submit" value="Enviar Formulário">
    </form>
</template>