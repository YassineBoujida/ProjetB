<template>

      <footer class="footer has-background-grey-lighter pl-6 pr-6" id="footer">
        <div class="container ">
          <div class="content pl-6 pr-6">
            <div class="columns">
              <div class="column  has-text-weight-bold">
                PRODUCT
              </div>
              <div class="column  has-text-weight-bold">
                COMPANY
              </div>
              <div class="column  has-text-weight-bold">
                HELP CENTER
              </div>
              <div class="column is-5 has-text-weight-bold">
                STAY IN TOUCH
              </div>
            </div>

            <div class="columns">
                <div class="column">
                  Personal
                </div>
                <div class="column">
                  About
                </div>
                <div class="column">
                  FAQ
                </div>
                <div class="column is-5">
                  Join our mail list to get updates. We respect your privacy.
                </div>
            </div>

              <div class="columns">
                <div class="column">
                  Business <br><br>
                  Pericing
                </div>
                <div class="column">
                  Blog <br><br>
                  Careers
                 
                </div>
                <div class="column">
                  Insurance <br><br>
                  Agreement
                </div>
                <div class="column is-5 pt-4">
                    <div class="control has-icons-left has-icons-right">
                        <input class="input is-rounded is-large" type="text" placeholder="Email address ...">
                        <span class="icon is-medium is-right">
                            <i class="fa fa-paper-plane"></i>
                          </span>
                    </div>
                    
                </div>
              </div>

              <div class="columns">
                <div class="column">
                  Login
                </div>
                <div class="column">
                  Contact Us
                </div>
                <div class="column">
                </div>
                <div class="column is-5">
                </div>
              </div>

              <div class="columns">
                <div class="column is-2 pt-6 pr-5">
                     <ImageComponent source="upshift.png" classFigure="image is-128x64" />
                </div>
                <div class="column pl-6 pt-6">
                  Copyright &#169; 2019 Upshift, Inc.
                </div>
                <div class="column is-5 pt-6">
                    <span class="icon">
                        <i class="fab fa-facebook-square"></i>
                    </span>
                    <span class="icon">
                        <i class="fab fa-twitter-square"></i>
                    </span>
                    <span class="icon">
                        <i class="fab fa-instagram"></i>
                    </span>
                </div>
              </div>

          </div>
        </div>
      </footer>
      
</template>

<script>


    import ImageComponent from "@/components/global_components/ImageComponent";
export default {

    name : "footerView",
    components:{
        // DistantImageComponent
        // ,ButtonComponent
        ImageComponent
    }
    
}
</script>

<style scoped>

</style>