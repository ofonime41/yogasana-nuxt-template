<template>
  <div>
    <div class="back_re">
         <div class="container">
            <div class="row">
               <div class="col-md-12">
                  <div class="title">
                        <h2>Pricing</h2>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <div class="pricing_main">
         <div class="container">
            <div class="row">
               <div class="col-md-12">
                  <div class="titlepage">
                   
                     <span>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy </span>
                  </div>
               </div>
              <Pricing />
            
            </div>
         </div>
      </div>
      <br><br><br>
  </div>
</template>

<script>
import Pricing from '../components/Pricing.vue';
export default {
    components: { Pricing }
}
</script>

<style>

</style>