<template>
   <div class="main-layout">

      <!-- our classes -->
      <div class="classes">
         <div class="container">
            <div class="row">
               <div class="col-sm-12">
                  <div class="titlepage">
                     <h2>Our Classes</h2>
                     <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                     </span>
                  </div>
               </div>
            </div>
            <Classes/>
         </div>
      </div>
      <!-- end our classes -->
      <!-- middle -->
      <div class="middle">
         <div class="container-fluid">
            <div class="row d_flex">
               <div class="col-md-6">
                  <div class="titlepage">
                     <h2 >The Inner Middle.</h2>
                     <p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptu</p>
                     <a class="read_more ye_b5n " href="Javascript:void(0)"> Read More</a>
                  </div>
               </div>
               <div class="col-md-5 offset-md-1 padding_right0">
                  <div class="yoga_img">
                     <figure><img src="~/assets/images/yoga_mo.png" alt="#"/></figure>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <!-- end middle -->
      <!-- about -->
      <div class="about">
         <div class="container-fluid">
            <div class="row">
               <div class="col-md-6 offset-md-3">
                  <div class="titlepage">
                     <h2>About Us</h2>
                     <span>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptu</span>
                  </div>
               </div>
               <About />
            </div>
         </div>
      </div>
      <!-- end about -->
      <!-- balance -->
      <div>
         <YogaComp />
      </div>
     
      <!-- end balance -->
      <!-- end middle -->
      <!-- pricing -->
      <div class="pricing_main">
         <div class="container">
            <div class="row">
               <div class="col-md-12">
                  <div class="titlepage">
                     <h2>Pricing</h2>
                     <span>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy </span>
                  </div>
               </div>
              <Pricing />
            </div>
         </div>
      </div>
      <br><br>
      <!-- end pricing -->
      <!-- pepole -->
      <div class="pepole">
         <div class="container">
            <div class="row">
               <div class="col-md-12">
                  <div class="titlepage">
                     <h2>What Says Pepole</h2>
                     <span>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy </span>
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-8 offset-md-2">
                  <div class="testimo_ban_bg">
                     <div id="testimo" class="carousel slide testimo_ban" data-ride="carousel">
                        <ol class="carousel-indicators">
                           <li data-target="#testimo" data-slide-to="0" class="active"></li>
                           <li data-target="#testimo" data-slide-to="1"></li>
                           <li data-target="#testimo" data-slide-to="2"></li>
                        </ol>
                        <div class="carousel-inner">
                           <div class="carousel-item active">
                              <div class="container parile0">
                                 <div class="carousel-caption relative2">
                                    <div class="row d_flex">
                                       <div class="col-md-12">
                                          <i><img class="qusright" src="~/assets/images/t.png" alt="#"/><img src="~/assets/images/tes.png" alt="#"/><img class="qusleft" src="~/assets/images/t.png" alt="#"/></i>
                                          <div class="aliq">
                                             <span>Aliqua</span>
                                             <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniamLorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam</p>
                                          </div>
                                       </div>
                                    </div>
                                 </div>
                              </div>
                           </div>
                           <div class="carousel-item">
                              <div class="container parile0">
                                 <div class="carousel-caption relative2">
                                    <div class="row d_flex">
                                       <div class="col-md-12">
                                          <i><img class="qusright" src="~/assets/images/t.png" alt="#"/><img src="~/assets/images/tes.png" alt="#"/><img class="qusleft" src="~/assets/images/t.png" alt="#"/></i>
                                          <div class="aliq">
                                             <span>Aliqua</span>
                                             <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniamLorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam</p>
                                          </div>
                                       </div>
                                    </div>
                                 </div>
                              </div>
                           </div>
                           <div class="carousel-item">
                              <div class="container parile0">
                                 <div class="carousel-caption relative2">
                                    <div class="row d_flex">
                                       <div class="col-md-12">
                                          <i><img class="qusright" src="~/assets/images/t.png" alt="#"/><img src="~/assets/images/tes.png" alt="#"/><img class="qusleft" src="~/assets/images/t.png" alt="#"/></i>
                                          <div class="aliq">
                                             <span>Aliqua</span>
                                             <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniamLorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam</p>
                                          </div>
                                       </div>
                                    </div>
                                 </div>
                              </div>
                           </div>
                           <a class="carousel-control-prev" href="#testimo" role="button" data-slide="prev">
                           <i class="fa fa-arrow-left" aria-hidden="true"></i>
                           <span class="sr-only">Previous</span>
                           </a>
                           <a class="carousel-control-next" href="#testimo" role="button" data-slide="next">
                           <i class="fa fa-arrow-right" aria-hidden="true"></i>
                           <span class="sr-only">Next</span>
                           </a>
                        </div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <!-- end pepole -->
      <!--  contact -->
      <div class="contact">
         <div class="container">
            <div class="row">
               <div class="col-md-12">
                  <div class="titlepage">
                     <h2>Contact Us</h2>
                  </div>
               </div>
            </div>
            <Contact />
         </div>
      </div>
      <!-- end contact -->
      
      <!-- end footer -->
     
    </div>
</template>

<script>
import Yoga from "../pages/yoga.vue";
export default {
    components: { Yoga }
}
</script>

<style>

</style>