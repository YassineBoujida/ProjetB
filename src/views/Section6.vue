<template>
       
      <section class="hero has-background-grey-lighter">
        <div class="hero-body mb-6">
            <div class="columns parent3">
                <div class="column pt-6 ml-6" >
                    <p class="about pt-6 has-text-weight-bold">05 ---------- THE CAR</p>
                    <h1 class="title is-2 pt-4 pb-4">
                        Always Drive an <br> Identical Prius
                    </h1>
                    <div class="content">
                        <p class="paragraph pb-4">
                            All our car are the same so they feel familiar. <br>
                            No branding so you don't stick out. <br>
                            <br>
                            Fits 5 comfortably - or a surfboard, bicycle, or skiis,<br>
                            54 MPG hybrid gets you to Tahoe and back on a <br>
                            single tank. Phone mount, charging cables, and <br>
                            Fastrak included. Bluetooth and safety technology <br>
                            like adaptive cruise control. We use all natural <br>
                            deodorizes and cleaning supplies.

                        </p>
                       
                    </div>
                   
                 </div>
                <div class="column pt-6 ml-6 section6-merging">
                <div class="columns">
                  <div class="column">
                    <ImageComponent source="car1.jpg" classFigure="image pr-6 img1" />
                    <div class="columns mt-4">
                        <div class="column">
                            <ImageComponent source="car2.jpg" classFigure="image img2" />
                        </div>
                        <div class="column">
                            <ImageComponent source="car3.jpg" classFigure="image img3" />
                        </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
        </div>
      </section>
</template>

<script>

import ImageComponent from "@/components/global_components/ImageComponent";

export default {

    name : "section6",
    components:{
        ImageComponent
    }
    
}
</script>

<style scoped>
.parent3 {
    position: relative;
    top: 0;
    left: 0;
  }

.section6-merging{
    position: absolute;
    top: -140px;
    right:120px;
}

.img1{
width: 290px;
height:260px;
}

.img2 {
width:150px;
height:260px;
}

.img3 {
width:300px;
height:220px;
}
</style>