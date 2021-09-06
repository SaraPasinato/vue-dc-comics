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

<style>
#socials{
    height: 13vh;
    width: 100%;
    background-color:#303030 ;
}

#socials .row{
    height: 100%;
    align-items: center;
    justify-content: space-around;
}

#socials h3{
    color: #0282f9;
    text-transform: uppercase;
    font-weight: bold;  
}

#items h3,
#items a{
    margin:5px;
}


</style>