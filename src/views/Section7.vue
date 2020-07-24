<template>
       
      <section class="hero has-background-grey-lighter">
        <div class="hero-body">

            <div class="columns">
              <div class="column is-9 pl-6">
                <h1 class="title mt-5 pl-6">
                    Join instantly with $0 down <br>
                    and get your car right now.
                </h1>
              </div>
              <div class="column mt-5 pr-6" >
                <ButtonComponent classButton="button mb-5 has-background-grey has-text-white is-rounded is-large is-fullwidth" buttonValue="Get started"/>
              </div>
            </div>

            <div class="columns mt-6 mb-5">
                <div class="column">
                </div>
                <div class="column is-10">
                    <hr class="navbar-divider has-background-grey-light">
                </div>
                <div class="column ">
                </div>
            </div>

        </div>
      </section>


</template>

<script>


  import ButtonComponent from "@/components/global_components/ButtonComponent";

export default {

    name : "section7",
    components:{
        ButtonComponent
    }
    
}
</script>

<style scoped>

</style>