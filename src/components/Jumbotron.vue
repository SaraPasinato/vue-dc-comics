<template>
  <section id="jumbotron">
   <div class="container-sm">
       <p><a href="#" class="btn btn-primary-full">Current Series</a></p>
   </div>
  </section>
</template>

<script>
export default {
 name:'Jumbotron',
}
</script>

<style lang='scss'>

#jumbotron{
    
    height: 40vh;

    background: url('../assets/img/jumbotron.jpg');
    background-position: top;
    background-size: cover;
    background-repeat: no-repeat;

    position: relative;

    .btn{
        position: absolute;
        bottom: -30px;
        left:325px;

        text-transform: uppercase;
        font-weight: bolder;
        font-size: 1.3em;
        padding: 10px 20px;
    }
}
</style>