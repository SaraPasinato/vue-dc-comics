<template>
  <section  id="mainContent" class="container">
    <section id="comics">
      <ComicCard v-for="(comic,index) in comicsData" :key="index" :card="comic" />
    </section>
    <div class="controls">
      <p><a href="#" class="btn btn-primary-full"> Load more</a></p>
    </div>
  </section>
</template>

<script>
import ComicCard from './ComicCard.vue';
import comicsData from '../assets/data/dc-comics.json';
export default {
  name: "Comics",
  components:{
    ComicCard,
  },
  data() {
    return {
      comicsData,
    };
  },
};
</script>

<style lang="scss">
@import "../assets/scss/_vars.scss";
@import "../assets/scss/style.scss";

#main-content{
  height: 100%;
  margin-bottom: 50px;
}
#comics {
  height: 100%;
  padding: 80px 0 10px 0 ;
  color: $light-color;

  display: flex;
  justify-content: center;
  flex-wrap: wrap;

 
}
 .controls{
   height: 20vh;
   text-align: center;
   line-height: 20vh;

   .btn{
     margin: 0 auto;
   }
  }
</style>