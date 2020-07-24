<template>
       <section class="hero has-background-white">
        <div class="hero-body">
            <div class="columns mt-5">
                <div class="column is-1"></div>
                <div class="column is-10 parent">
                    <div class="box card2 pr-6 pl-6">
                        <article class="media">
                          <div class="media-content pt-5 pb-5 pl-5 pr-5">
                            <div class="content section4 pr-6 pl-6">
                                <p class="pt-6 has-text-white">03 ---------- SERVICE ZONE</p>
                                <h1 class="title has-text-white">We've got SF covered</h1>
                                <p class="has-text-grey-light">We provide two delivery options for any trip :</p>
                                <h4 class="subtitle is-6">
                                    <i class="fa fa-check mr-5"></i> <span class="has-text-white"> Concierge service (8am-8pm daily) </span>
                                </h4>
                                <p class="has-text-grey-light ml-6">
                                    We delivery or pick up at your doorstep. Always <br>
                                    have a parking spot right out front, just for you.
                                </p>
                                <h4 class="subtitle is-6">
                                    <i class="fa fa-check mr-5"></i> <span class="has-text-white"> Self service (24/7) </span>
                                </h4>
                                <p class="has-text-grey-light ml-6">
                                    We delivery or pick up at your doorstep. Always <br>
                                    have a parking spot right out front, just for you.
                                </p>
                                <div class="columns mt-5">
                                    <div class="column is-11">
                                        <hr class="navbar-divider has-background-grey-light">
                                    </div>
                                    </div>
                                </div>

                                <div class="columns mt-5 pr-6 pl-6">
                                <div class="column is-one-fifth">
                                    <DistantImageComponent classFigure="image is-64x64" source="https://thumbs.dreamstime.com/b/vector-logo-self-service-car-wash-vector-logo-self-service-car-wash-172733700.jpg" classImage="is-rounded"/> 
                                </div>
                                <div class="column pt-4 pl-5">
                                    <p class="has-text-grey-light">
                                        ouside of SF ?
                                    </p>
                                    <a href="#" class="has-text-white">
                                        Tell us where to expand <i class="fa fa-arrow-right" aria-hidden="true"></i>
                                    </a>
                                    
                                </div>
                                </div>
                          </div>
                        </article>
                    </div>

                    <img class="image merging-img-section4" src="../assets/concierge.jpg" >
                </div>
            </div>

        </div>
      </section>
        
</template>

<script>

   import DistantImageComponent from "@/components/global_components/DistantImageComponent";


export default {

    name : "section4",
    components:{
        DistantImageComponent
    }
    
}
</script>

<style scoped>
.card2 {
    position: absolute;
    top: 110px;
    left:355px;
  }

.merging-img-section4 {
    position: relative;
    top: 0;
    left: 0;
    width:400px;
    height:650px;
  }

</style>