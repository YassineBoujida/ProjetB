<template>
    
        <div class="box is-shadowless">
                        <article class="media">
                          <div class="media-content">
                            <div class="content">
                                <div class="columns mt-5">
                                    <div class="column is-flex is-horizontal-center">
                                        <DistantImageComponent classFigure="image is-64x64" :source="load_image()" classImage="is-rounded"/>
                                    </div>
                                </div>
                                <h1 class="title">{{title}}</h1>
                                <p class="paragraph" v-html="content">
                                </p>
                            </div>
                          </div>
                        </article>
        </div>
 
</template>


<script>

import DistantImageComponent from "@/components/global_components/DistantImageComponent";

export default {
    name : "card_component",
    props : ['title','content'],
    components:{
        DistantImageComponent
    },
    methods:{
        load_image(){
            if(this.title=='Text Us')
            return "https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTytgUdKKfQvl2sipDN5IM16139M8Cg_OkiprXMN9bi5g&usqp=CAU&ec=45682160";
            else 
            {
                if(this.title=="We deliver")
                    {
                        return "https://www.pinclipart.com/picdir/middle/116-1168878_download-grande-feirao-clipart-car-four-wheel-drive.png";
                    }
                else
                {
                    if(this.title=="You drive"){
                        return "https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRn9LOEU-jaePSbxLcHgusqLMho7PkmZKQ2XA&usqp=CAU";
                    }
                    else{
                        return "https://cdn5.f-cdn.com/contestentries/1488134/33049642/5cb0219b29d81_thumb900.jpg";
                    }
                }
                    
            }

        }
    }
}
</script>

<style scoped>
.box{
    border-bottom : 1px solid rgb(194, 187, 187);
    border-radius: 0px;
}
</style>