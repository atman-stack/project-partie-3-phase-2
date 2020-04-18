<template>
    <section class="section  my-0"  >



                <div class="col-lg-12 ">
                  
                        <b-carousel id="carousel1"
                                    controls
                                    indicators
                                    
                                    >
                            <!-- Text slides with image -->
                            <b-carousel-slide   img-src="img/theme/clinic-1807543_1280.jpg">  
                                      <div class="bg-light text-default font-weight-bold" > 
                                        
                                                        <h5  >accueil</h5>
                                                                        
                                                                            <p>Il y a tout juste un mois, une étude franco américaine montrait que des chiens pouvaient sentir l’odeur des crises d’épilepsie.  </p>
                                      </div>
                                 </b-carousel-slide>
                            <b-carousel-slide img-src="img/theme/surgery-1822458_1280.jpg">   
                                               <div class="bg-light text-default font-weight-bold"  >
                                                 <h5 >blog</h5>
                                                                            <p >Des scientifiques français ont découvert un déficit métabolique qui serait à la base des troubles cognitifs liés à Alzheimer.</p>
                                                  </div>
                                 </b-carousel-slide>
                                <b-carousel-slide img-src="img/theme/bethesda-naval-medical-center-80380_1280.jpg">   
                                                  <div class="bg-light text-default font-weight-bold" >
                                                                <h5>contact</h5>
                                                                                                <p >Impulsion électrique, ultrasons, ondes électromagnétiques… Et si les outils physiques prenaient un jour la place des médicaments neurologiques dans notre trousse à pharmacie ?</p>
                                                  </div>                             
                                 </b-carousel-slide>
                        </b-carousel>
                  
                </div>

    </section>
</template>
<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
  components: {
    BCarousel,
    BCarouselSlide
  }
};
</script>
<style>
</style>
