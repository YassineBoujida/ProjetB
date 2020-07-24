<template>
    <section class="hero">
        <div class="hero-body">
            <div class="columns mt-6">
                <div class="column pl-6" >
                    <h1 class="title is-1">
                        Just drive.
                    </h1>
                    <h1 class="title is-1">
                        We'll do the rest.
                    </h1>
                    <p class="pt-5 pb-6">All-inclusive, usage-based car subscriptions.</p>
                    <div class="columns">
                        <div class="column">
                            <div class="field">
                                <div class="control">
                                  <input class="input input-section1 is-medium has-background-grey-lighter is-6" type="text" placeholder="Phone number...">
                                </div>
                            </div>
                        </div>
                        <div class="column">
                            <p class="control">
                                <ButtonComponent classButton="button is-medium is-rounded has-background-grey-dark has-text-white" buttonValue="Get started"/>
                            </p>
                        </div>
                    </div>
                </div>
                <div class="column"  style="text-align: center;" >
                        <DistantImageComponent source="https://5.imimg.com/data5/CP/IT/MY-583488/automated-manual-transmission-28amt-29-500x500.jpg" />
                </div>
            </div>

            <div class="columns mt-6">
              <div class="column is-four-fifths has-background-white">
                <div class="columns">
                  <div class="column">
                    <ImageComponent source="BI.png" classFigure="image is-128x64" />
                  </div>
                  <div class="column">
                    <ImageComponent source="wired.png" classFigure="image is-128x64" />
                  </div>
                  <div class="column">
                    <ImageComponent source="urbanx.png" classFigure="image is-128x64" />
                  </div>
                  <div class="column">
                    <ImageComponent source="metropolis.png" classFigure="image is-128x64" />
                  </div>
                  <div class="column">
                    <ImageComponent source="curbed.png" classFigure="image is-128x64" />
                  </div>
                </div>
              </div>

              <div class="column pt-6"  style="text-align: center;">
                <a href="#footer"><i class="fa fa-arrow-down fa-3x"></i></a>
              </div>
              
            </div>
        </div>
    </section>
</template>

<script>

import ImageComponent from "@/components/global_components/ImageComponent";
import DistantImageComponent from "@/components/global_components/DistantImageComponent";
import ButtonComponent from "@/components/global_components/ButtonComponent";

export default {

    name : "section1",
    components:{
        ImageComponent,ButtonComponent,DistantImageComponent
    }
    
}
</script>

<style scoped>

.input-section1{
    border-bottom: 1px solid purple
}

.container{
    margin:0 !important;
    padding:0 !important;
}



</style>