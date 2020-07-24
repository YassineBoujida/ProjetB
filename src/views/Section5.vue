<template>
       <section class="hero has-background-white">
            <div class="hero-body">
                <div class="columns mt-6">
                    <div class="column mt-6" style="text-align: center;">
                                    <p class="pt-6 about has-text-weight-bold">04 ---------- PRICING</p>
                                    <h1 class="title mt-5">Monthly plans for less than a parking space</h1>
                                    <p class="paragraph mt-6">
                                        plans include concierge delivery and pickup, cleaning and refueling service,
                                         full covergae insurance <br> and maintenance-everything but gas and tolls. 
                                         join instantly with $0 down and get your car right now.
                                    </p>
                                    
                    </div>
                </div>

                <div class="columns mb-6" style="text-align:center">
                    <div class="column is-1"></div>
                    <div class="column pt-6 mt-6">
                        <PlanCardComponent title="FlexPass" subtitle="Get 2 days/month" price="$159<sub>/month</sub>" content="Not sure how much you drive ? <br>
                                        Get a magic button anytime you <br>
                                        need a car."/>
                    </div>
                    <div class="column pt-6">
                        <PlanCardComponent title="Getaway" subtitle=" Get 4 days/month" price="$219<sub>/month</sub>" 
                                          content=" Get away up to once a week.<br>
                                        Your car is delivered and <br>
                                        disappears - like magic." show="showRecommanded"/>
                    </div>
                    <div class="column pt-6 mt-6">
                         <PlanCardComponent title="Freedom" subtitle="Get 8 days/month" price="$389<sub>/month</sub>" 
                                          content="Get a car up to twice a week. It's<br>
                                        freedom whenever you want it (and <br> 
                                        no additional fees when you don't)."/>
                    </div>
                    <div class="column is-1"></div>
                
                </div>

            </div>
    </section>
        
</template>

<script>



import PlanCardComponent from "@/components/global_components/PlanCardComponent";

export default {

    name : "section5",
    components:{
        PlanCardComponent
    },
    data(){
        return {
            showRecommanded : true
        }
    }
    
}
</script>

<style scoped>
</style>