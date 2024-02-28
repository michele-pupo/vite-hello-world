<script>
   // importare un componente
   import AppTitle from './components/AppTitle.vue';

   export default{

      // dichiariamo i componenti
      components: {
         AppTitle,
      },

      data() {
         return {
            message: "Hello Vite!"
         }
      },
   }
</script>

<template>
   <AppTitle></AppTitle>
</template>

<style>

</style>
