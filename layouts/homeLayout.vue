<template>
  <div>
    <header class="full_bg">
      <!-- <Loader/> -->
         <NavBar/>
        <section class="banner_main">
            <div id="myCarousel" class="carousel slide banner" data-ride="carousel">
               <ol class="carousel-indicators">
                  <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                  <li data-target="#myCarousel" data-slide-to="1"></li>
                  <li data-target="#myCarousel" data-slide-to="2"></li>
               </ol>
               <div class="carousel-inner">
                  <div class="carousel-item active">
                     <div class="container">
                        <div class="carousel-caption  banner_po">
                           <div class="row">
                              <div class="col-md-5">
                                 <div class="yo_img">
                                    <figure><img src="~/assets/images/yo_img.png" alt="#"/></figure>
                                 </div>
                              </div>
                              <div class="col-md-7">
                                 <div class="yoga_box">
                                    <span>Now started</span>
                                    <h1> <strong>Y</strong> O <strong>G</strong> A</h1>
                                    <a class="read_more yoga_btn" href="contact.html" role="button">Contact us</a>
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                  </div>
                  <div class="carousel-item">
                     <div class="container">
                        <div class="carousel-caption banner_po">
                           <div class="row">
                              <div class="col-md-5">
                                 <div class="yo_img">
                                    <figure><img src="~/assets/images/yo_img.png" alt="#"/></figure>
                                 </div>
                              </div>
                              <div class="col-md-7">
                                 <div class="yoga_box">
                                    <span>Now started</span>
                                    <h1> <strong>Y</strong> O <strong>G</strong> A</h1>
                                    <a class="read_more yoga_btn" href="contact.html" role="button">Contact us</a>
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                  </div>
                  <div class="carousel-item">
                     <div class="container">
                        <div class="carousel-caption banner_po">
                           <div class="row">
                              <div class="col-md-5">
                                 <div class="yo_img">
                                    <figure><img src="~/assets/images/yo_img.png" alt="#"/></figure>
                                 </div>
                              </div>
                              <div class="col-md-7">
                                 <div class="yoga_box">
                                    <span>Now started</span>
                                    <h1> <strong>Y</strong> O <strong>G</strong> A</h1>
                                    <a class="read_more yoga_btn " href="contact.html" role="button">Contact us</a>
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                  </div>
               </div>
               <a class="carousel-control-prev" href="#myCarousel" role="button" data-slide="prev">
               <i class="fa fa-arrow-left" aria-hidden="true"></i>
               <span class="sr-only">Previous</span>
               </a>
               <a class="carousel-control-next" href="#myCarousel" role="button" data-slide="next">
               <i class="fa fa-arrow-right" aria-hidden="true"></i>
               <span class="sr-only">Next</span>
               </a>
            </div>
        </section>
      </header>

      <Nuxt />
      <FooterBar />
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>