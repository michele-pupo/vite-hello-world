<script>

    //importare un componente 
    import AppTitle from './AppTitle.vue';

    export default{
    name: 'AppHero',
    components: { AppTitle }
}
</script>

<template>
   <jumbotron>
        <div id="jumbotron">
            <AppTitle></AppTitle>
            <img src="../../img/7c29fa5a6267c7f1ac9e859ffd5bef80ac282556.jpeg" alt="">
        </div>
   </jumbotron>
</template>

<style>
    #jumbotron{
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
</style>