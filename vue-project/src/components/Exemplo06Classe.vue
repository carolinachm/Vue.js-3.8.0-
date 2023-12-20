<!--script-->
<script setup>
//variaveis
let validacao = false


</script>
<!--Css-->
<style>
.ok {
    color: green;
}

.falha {
    color: red;
}
</style>
<!--HTML-->
<template>
    <p :class="validacao ? 'ok' : 'falha'">Utilizando a diretiva class</p>
</template>