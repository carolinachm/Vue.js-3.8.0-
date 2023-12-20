<!--script-->
<script setup>
   //função

   function mensagem(){
    alert('Trabalhando com eventos de clique')
   }

</script>
<!--HTML-->
<template>
   
  <button @click="mensagem()">Clique aqui</button>
   
</template>