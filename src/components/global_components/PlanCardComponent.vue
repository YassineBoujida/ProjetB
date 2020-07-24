<template>
        
        <div class="box">
                            <article class="media">
                              <div class="media-content">
                                <div class="content  pl-5 pr-5">
                                    <p class="paragraph2 has-text-weight-bold" v-show="show">RECOMMENDED</p>
                                    <h1 class="title">{{title}}</h1>
                                    <p class="paragraph">
                                     {{subtitle}}
                                    </p>
                                    <h1 class="title is-3" v-html="price"> </h1> 

                                    <div class="columns mt-5">
                                        <div class="column">
                                            <hr class="navbar-divider has-background-grey-light">
                                        </div>
                                    </div>
                                    <p class="paragraph mb-6" v-html="content">
                                    </p>
                                    <ButtonComponent classButton="button mb-5 has-background-grey has-text-white is-rounded is-medium is-fullwidth" :buttonValue="buttonValue()"/>
                                    <a href="#" class="paragraph2">
                                        View plan details <i class="fa fa-arrow-right" aria-hidden="true"></i>
                                    </a>
                                </div>
                              </div>
                            </article>
                        </div>
</template>


<script>

import ButtonComponent from "@/components/global_components/ButtonComponent";

export default {
    name : "plan_card_component",
    props : ['title','subtitle','price','content','show'],
    components:{
        ButtonComponent
    },
    methods:{
        buttonValue(){
            if(this.title=='FlexPass')
            return "Start with FlexPass";
            else 
            {
                if(this.title=="Getaway")
                    {
                        return "Start with Getaway";
                    }
                else
                    return "Start with freedom";
            }

        }
    }
}
</script>

<style scoped>

</style>