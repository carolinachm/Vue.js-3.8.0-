<!--script-->
<script setup>
    //import o ref
    import { ref } from 'vue';

    //variaveis
    let texto = ref('')

</script>
<!--HTML-->
<template>
   
   <input type="text" v-model="texto">
   <p>{{ texto }}</p>
   
</template>