<template>
  <div id="app">
  <Header/>
  <main>
    <Comics/>
    <SiteLinks/>
  </main>
  <footer>
    <FooterLinks/>
    <FooterSocials/>
  </footer>
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import FooterLinks from "@/components/FooterLinks.vue";
import FooterSocials from "@/components/FooterSocials.vue";
import Comics from "@/components/Comics.vue";
import SiteLinks from "@/components/SiteLinks.vue";
export default {
  name: 'App',
  components: {
   Header,
   Comics,
   FooterLinks,
   FooterSocials,
   SiteLinks,
  }
}
</script>

<style lang="scss">
//!Generics
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
.container-sm{
  max-width: 1300px;
  margin: 0 auto;
}

.row{
  display: flex;
  
}

.col-6{
  flex-basis: 100%/2;
}
//!Utils
li {
  list-style-type: none;
  a {
    text-decoration: none;
    padding: 0 15px 32px 15px;
    color: #303030;

    text-transform: uppercase;
    font-weight: bold;
    font-size: 0.9em;
  }
  a:hover {
    color: #0282f9;
  }
}


.list-nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.list-nav-center {
  display: flex;
  justify-content: center;
  align-items: center;
}

.link-sm{
  font-size: 1em;
  color: #919090;
}

.active{
  border-bottom: 5px solid #0282f9;
  color: #0282f9;
}

.btn{
  padding:20px;
  text-decoration: none;
  text-transform: uppercase;
}
.btn.btn-primary{
  color: #fff;
  border: 2px solid #0282f9;
}

//!margins & widths
.mt-3{
  margin-top: 2em;
}

.w-15{
    width:15%;
}
.w-10{
    width:10%;
}
.w-40{
    width:40%;
}


</style>
