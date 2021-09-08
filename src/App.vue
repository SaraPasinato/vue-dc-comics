<template>
  <div id="app">
  <Header/>
  <main>
    <Comics />
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
  },
}
</script>

<style lang="scss">
@import 'assets/scss/style.scss';
</style>
