<!--script-->
<script setup>
    //variave
    let nome = 'Nina'
    let idade = 40
    let numero1 = 1
    let numero2 = 2
</script>
<!--HTML-->
<template>
    <p>{{ "Olá " + nome + " eu tenho" + idade + " anos"}}</p>
    <p>{{ numero1 + numero2 }}</p>
    <p>{{ numero1 * numero2 }}</p>
</template>