<template>
   
      <div class="header">
            <div class="container-fluid">
               <div class="row">
                  <div class="col-xl-3 col-lg-3 col-md-3 col-sm-3 col logo_section">
                     <div class="full">
                        <div class="center-desk">
                           <div class="logo">
                              <a href="index.html"><img src="~/assets/images/logo.png" alt="#" /></a>
                           </div>
                        </div>
                     </div>
                  </div>
                  <div class="col-xl-9 col-lg-9 col-md-9 col-sm-9">
                     <nav class="navigation navbar navbar-expand-md navbar-dark ">
                        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExample04" aria-controls="navbarsExample04" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse" id="navbarsExample04">
                           <ul class="navbar-nav mr-auto">
                              <li class="nav-item ">
                                 <router-link to="/" class="nav-link" >Home</router-link >
                              </li>
                              <li class="nav-item">
                                 <router-link to="/about" class="nav-link" >About</router-link>
                              </li>
                              <li class="nav-item active">
                                 <router-link to="/classes" class="nav-link">classes</router-link>
                              </li>
                              <li class="nav-item">
                                 <router-link to="/yoga"  class="nav-link" >yoga</router-link>
                              </li>
                              <li class="nav-item">
                                 <router-link to="/pricing" class="nav-link" >pricing</router-link>
                              </li>
                              <li class="nav-item">
                                 <router-link to="/contact" class="nav-link" >Contact Us</router-link>
                              </li>
                           </ul>
                        </div>
                     </nav>
                  </div>
               </div>
            </div>
         </div>
   
      
      


  
</template>

<script>
export default {

}
</script>

<style>

</style>