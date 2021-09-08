<template>
  <div class="card">
    <img :src="card.thumb" :alt="card.series + card.type">
    <h5>{{ card.series }}</h5>
    <h6>{{ card.type}}</h6>
  </div>
</template>

<script>
export default {
 name:'ComicCard',
 props:['card'],
}
</script>

<style lang="scss" >
@import '../assets/scss/_vars.scss';

 .card{
     flex-basis: calc(100%/6);
     color: $light-color;
     text-align: center;
     margin: 0.6rem;

     img{
         max-width: 50%;
        transform: scale(1.5,1);
     }

     h5{
         text-transform: uppercase;
     }

     h6{
         font-style: italic;
         font-weight:200;
     }
 }
 
</style>