<template>
  <section id="socials">
      <div class="row container">
          <div class="col-6">
            <a href="#" class="btn btn-primary">Sign-up now</a>
          </div>
          <div class="col-6">
              <div id="items" class="row">
                  <h3>Follow us</h3>
                  <a href="" class=""><img src="../assets/img/footer-facebook.png" alt=""></a>
                  <a href="" class="btn-rounded "><img src="../assets/img/footer-twitter.png" alt=""></a>
                  <a href="" class=""><img src="../assets/img/footer-youtube.png" alt=""></a>
                  <a href="" class=""><img src="../assets/img/footer-pinterest.png" alt=""></a>
                  <a href="" class=""><img src="../assets/img/footer-periscope.png" alt=""></a>
                
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
  name:'FooterSocials'
}
</script>

<style lang="scss">
@import '../assets/scss/_vars.scss';
//!Footer Social
#socials{
    height: 10vh;
    width: 100%;
    background-color:$dark-secondary-color ;

    .row{
        height: 100%;
        align-items: center;
        justify-content: space-around;
    }
    
    h3{
        color: $prime-color;
        text-transform: uppercase;
        font-weight: bold;  
    }
}
//!items in social section
#items h3,
#items a{
    margin:5px;
}


</style>