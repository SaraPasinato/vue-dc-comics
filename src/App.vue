<template>
  <div id="app">
  <Header/>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
export default {
  name: 'App',
  components: {
   Header,
  }
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin:0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body{
  background-color: #000;
}

img{
  width:100%;
  height: auto;
}

.container{
  max-width: 1500px;
  margin: 0 auto;
}

.row{
  display: flex;

}
</style>
