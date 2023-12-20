<!--script-->
<script setup>
    //variaveis
    let nomes = ['Ana', 'Maria', 'Carolina', 'Jão']

</script>
<!--HTML-->
<template>
   <ul>
    <li v-for="nome in nomes">{{ nome }}</li>
   </ul>
   
</template>