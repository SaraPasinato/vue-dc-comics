<template>
  <div id="app">
  <Header/>
  <main>
    <Comics/>
  </main>
  <footer>
    <FooterLinks/>
  </footer>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import FooterLinks from "@/components/FooterLinks.vue";
import Comics from "@/components/Comics.vue";
export default {
  name: 'App',
  components: {
   Header,
   Comics,
   FooterLinks,
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

.col-6{
  flex-basis: 100%/2;
}

li {
  list-style-type: none;
}

li a {
  text-decoration: none;
  padding: 44px 20px;
  
  text-transform: uppercase;
  font-weight: bold;
  font-size: 0.9em;
}

li a:hover {
  color: #0282f9;
}

.link-sm{
  font-size: 0.8em;
}

</style>
