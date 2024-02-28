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
            <img src="/vite.svg" alt="">
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

    img{
        width: 500px;
    }
</style>