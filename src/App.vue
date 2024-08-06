<template>
  <BonjourCoach :sub-title="subTitle" />
  

  <input type="text" v-model="subTitle"> 
</template>

<script setup>
  import BonjourCoach from '@/components/BonjourCoach.vue';

  const subTitle =  "Voici ma realisation sur ce projet.";
</script>

<style scoped>

</style>


