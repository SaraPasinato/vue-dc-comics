<template>
  <section id="footer-links" class="">
  <div class="container row">
          <div class="col-6">
             <div class="row">
                 <div class="col">
                      <h3>DC Comics</h3>
                      <ul class="link-sm">
                          <li><a href="#"></a>Characters</li>
                          <li><a href="#"></a>Comics</li>
                          <li><a href="#"></a>Movies</li>
                          <li><a href="#"></a>TV</li>
                          <li><a href="#"></a>Games</li>
                          <li><a href="#"></a>Videos</li>
                          <li><a href="#"></a>News</li>
                      </ul>
                      <h3>Shop</h3>
                      <ul class="link-sm">
                          <li><a href="#"></a>Shop DC</li>
                          <li><a href="#"></a>Shop DC Collections</li>
                      </ul>
                  </div>
                  <div class="col">
                      <h3>DC</h3>
                      <ul class="link-sm">
                          <li><a href="#"></a>Terms of Use</li>
                          <li><a href="#"></a>Privacy policy(New)</li>
                          <li><a href="#"></a>Ad Choices</li>
                          <li><a href="#"></a>Advertising</li>
                          <li><a href="#"></a>Jobs</li>
                          <li><a href="#"></a>Subscriptions</li>
                          <li><a href="#"></a>Talent Workshops</li>
                          <li><a href="#"></a>CPSC Certificates</li>
                          <li><a href="#"></a>Ratings</li>
                          <li><a href="#"></a>Shop Help</li>
                          <li><a href="#"></a>Contact Us</li>
                      </ul>
                  </div>
                  <div class="col">
                      <h3>Site</h3>
                      <ul class="link-sm">
                          <li><a href="#"></a>DC</li>
                          <li><a href="#"></a>MAD Megazine</li>
                          <li><a href="#"></a>DC Kids</li>
                          <li><a href="#"></a>DC Universe</li>
                          <li><a href="#"></a>DC Power VISA</li>
                      </ul>
                  </div>
             </div> 
          </div>

      <div id="logo-link" class="col-6">
      </div>
  </div>
  </section>
</template>

<script>
export default {
 name:'FooterLinks',
}
</script>

<style>
#footer-links{
    height: 40vh;

    background: url('../assets/img/footer-bg.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    
}

#footer-links .row{
    height: 100%;
    align-items: flex-start;
    justify-content: space-around;
}

.col h3{
  margin-left: 40px;
  margin-bottom: 10px;
  margin-top: 10px;
  text-transform: uppercase;
  color:#fff;
}

.col .link-sm{
    color: #919090;
}

#logo-link.col-6{
 align-self: center;
}

#logo-link{
    width:30%;
    height: 100%;
    background:url('../assets/img/dc-logo-bg.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    z-index: 1;
}

</style>