<template>
    <section class="hero has-background-white">
        <div class="hero-body">
              <div class="columns mt-6 mb-6">
                <div class="column pt-3 pl-6">
                    <p class="about has-text-weight-bold">02 ---------- HOW IT WORKS</p>
                    <h1 class="title is-2 pt-4 pb-4">
                        Simple and <br> handy rental process
                    </h1>
                </div>

                <div class="column pt-6 pl-6">

                    <div class="content content2">
                        <p class="paragraph pb-4">
                            Snow chaine, surf board ruck, key lock box, or <br>
                            dog car seat hammock available upon request.
                        </p>
                        
                        <hr class="navbar-divider has-background-grey-light">
                      
                        
                        <div class="columns mt-5">
                            <div class="column is-one-fifth">
                            <DistantImageComponent classFigure="image is-64x64" source="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTMyphvqWbKBCicfg9CkF163bt47HQVNoNPtQ&usqp=CAU" classImage="is-rounded"/>
                            </div>
                            <div class="column pt-5 pl-5">
                                <a href="#" class="paragraph2">
                                    Check the available accessoiries <i class="fa fa-arrow-right" aria-hidden="true"></i>
                                </a>
                                
                            </div>
                        </div>
                    </div>

                </div>

                <div class="column pt-6 pl-6">
                    <div class="content content2">
                        <p class="paragraph pb-4">
                           Still got questions? We've probably covered<br>
                           them all in the help center.
                        </p>
                        
                        <hr class="navbar-divider has-background-grey-light">
                      
                        
                        <div class="columns mt-5">
                            <div class="column is-one-fifth">
                                <DistantImageComponent classFigure="image is-64x64" source="https://fiverr-res.cloudinary.com/images/t_main1,q_auto,f_auto,q_auto,f_auto/gigs/120714484/original/f8024a2e696b74465fb4f6e2fda5135045bbf227/write-a-mysql-or-mariadb-database-query.png" classImage="is-rounded"/>
                            </div>
                            <div class="column pt-5 pl-5">
                               
                                <a href="#" class="paragraph2">
                                    Read our fAQ <i class="fa fa-arrow-right" aria-hidden="true"></i>
                                </a>
                                
                            </div>
                        </div>
                    </div>
                </div>
              </div>

              <div class="columns pt-6" style="text-align: center;">
                <div class="column">
                    <CardComponent title="Text Us" content="Text when you want your car.<br>
                                No app needed, just an online<br>
                                account. Real human operators.
                                "/>
                </div>

                <div class="column pt-6">
                    <CardComponent title="We deliver" content="Your car will arrive at<br>
                                  your door-clean and<br>
                                  fully fueled."/>
                </div>

                <div class="column">
                    <CardComponent title="You drive" content=" Hope in and go with full coverage<br>
                                  insurance, Fastrack, phone<br>
                                  accessoiries, and unlimited mileage."/>
                </div>

                <div class="column pt-6">
                    <CardComponent title="We pick it up" content="It's your for a few hours or a few <br> days.
                                  Return on your own time, anywhere in
                                  our zone, We'll gas<br> and clean it."/>
                </div>

                

                
                
              </div>

        </div>
      </section>
        
</template>

<script>

import DistantImageComponent from "@/components/global_components/DistantImageComponent";
import CardComponent from "@/components/global_components/CardComponent";

export default {

    name : "section3",
    components:{
        DistantImageComponent, CardComponent
        // ,ButtonComponent
    }
    
}
</script>

<style scoped>


</style>