<template>
  <nav id="site">
      <div class="row container-sm">
          <ul class="list-nav-center">
              <li class="list-nav-li">
                  <img src="@/assets/img/buy-comics-digital-comics.png" alt="" class="w-15">
                  <a href="">Digital comics</a>
               </li>
              <li class="list-nav-li">
                  <img src="@/assets/img/buy-comics-merchandise.png" alt="" class="w-15">
                  <a href="">Dc merchandise</a>
               </li>
              <li class="list-nav-li">
                  <img src="@/assets/img/buy-comics-subscriptions.png" alt="" class="w-15">
                  <a href="">subscriptions</a>
               </li>
              <li class="list-nav-li">
                  <img src="@/assets/img/buy-comics-shop-locator.png" alt="" class="w-10">
                  <a href="">Comics shop locator</a>
               </li>
              <li class="list-nav-li">
                  <img src="@/assets/img/buy-dc-power-visa.svg" alt="" class="w-15">
                  <a href="">Dc power visa</a>
               </li>
            
          </ul>
      </div>
  </nav>
</template>

<script>

export default {
 name :'SiteLinks',
}
</script>

<style lang="scss">
@import '@/assets/scss/_vars.scss';
@import url('/assets/scss/style.scss');
//!site section
#site{
    height: 20vh;
    background:$prime-color ;

    .row{
        height: 100%;
    }
}

.list-nav-li{
    display: flex;
    justify-content: center;
    flex-basis: calc(100%/5);

   a{
    padding:0  20px;
    align-self: center;
    color:$light-color;

    }

   a:hover{
    color: $light-color;
    }
}

</style>