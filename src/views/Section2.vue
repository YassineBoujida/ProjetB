<template>
    <section class="hero has-background-white">
        <div class="hero-body">
            <div class="columns mt-6">
                <div class="column pt-6 pr-6 pl-6 parent">
                       <img class="image merging-img" src="../assets/buy_car.jpg">
                        <div class="box card">
                            <article class="media">
                              <div class="media-content pt-5 pb-5 pl-5 pr-5">
                                <div class="content">
                                  <p class="has-text-white pl-6 since-paragraph">
                                    "Since becoming a monthly subscriber, i feel like<br>
                                    I have my car back again. it's like I own a car without <br>
                                    the worries or cost  of keeping it around all the time."
                                  </p>
                                  <div class="columns ">
                                    <div class="column is-one-fifth pl-5 pt-6">
                                      <ImageComponent classFigure="image is-48x48" source="sam.jpg" classImage="is-rounded"/>
                                    </div>
                                    <div class="column is-two-fifths has-text-white pl-5 pt-6"><p class="pt-3 pl-3">SAM R.</p></div>
                                    <div class="column pl-6 pt-6">
                                            <i class="fa fa-star" aria-hidden="true"></i>
                                            <i class="fa fa-star" aria-hidden="true"></i>
                                            <i class="fa fa-star" aria-hidden="true"></i>
                                            <i class="fa fa-star" aria-hidden="true"></i>
                                            <i class="fa fa-star" aria-hidden="true"></i>
                                            <p class="has-text-grey is-size-7">28 reviews at Yelp</p>
                                    </div>
                                  </div>
                                </div>
                                    
                              </div>
                            </article>
                        </div>
                </div>
                <div class="column pt-6 ml-6" >
                    <p class="about pt-6 has-text-weight-bold">01 ---------- ABOUT US</p>
                    <h1 class="title is-2 pt-4 pb-4">
                        Let's make cities better
                    </h1>
                    <div class="content">
                        <p class="paragraph pb-4">
                            Upshift is like having your own car at your doorstep, but only <br>
                            the days you want it. Monthly plans based on how much you <br>
                            drive that include parking, insurance, maintenance and more.<br><br>
                            We believe in using business to drive positive change in the<br>
                            world and never settling for what worked in the past.
                        </p>
                        <div class="columns mt-5">
                        <div class="column is-two-thirds">
                            <hr class="navbar-divider has-background-grey-light">
                        </div>
                        </div>
                        
                        <div class="columns mt-5">
                            <div class="column is-one-fifth">
                                <DistantImageComponent classFigure="image is-64x64" source="https://vanakdairy.ir/wp-content/uploads/2017/05/about-us-icon-15-1.png" classImage="is-rounded"/>
                            </div>
                            <div class="column">
                                <p class="paragraph">
                                    Interested in our values ?
                                </p>
                                <a href="#" class="paragraph2">
                                    Learn more about the company <i class="fa fa-arrow-right" aria-hidden="true"></i>
                                </a>
                                
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
   import DistantImageComponent from "@/components/global_components/DistantImageComponent";

export default {

    name : "section2",
    components:{
        ImageComponent, DistantImageComponent
    }
    
}
</script>

<style scoped>





.since-paragraph{
    border-left: 2px solid gray;
}

.fa-star{
    color:yellow
}


.merging-img {
    position: relative;
    top: 0;
    left: 0;
    width:320px;
    height:450px
  }
  .card {
    position: absolute;
    top: 320px;
    left: 80px;
  }

</style>