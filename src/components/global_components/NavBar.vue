<template>
     <nav class="navbar has-background-grey-lighter is-fixed-top">
        <div class="navbar-brand">
            <a class="navbar-item mr-6" >
            <img src="../../assets/upshift.png" width="112" height="28">
            </a>

            <div class="navbar-burger burger" data-target="navMenubd-example">
            <span></span>
            <span></span>
            <span></span>
            </div>
        </div>

        <div id="navMenubd-example" class="navbar-menu">
            <div class="navbar-start">
            
            <a class="navbar-item has-text-weight-bold">
                <i class="fa fa-circle mr-2" aria-hidden="true"></i>
                Personal
                
            </a>
       
            <a class="navbar-item has-text-weight-bold">
                <i class="fa fa-circle mr-2" aria-hidden="true"></i>
                Business
            </a>
            </div>
            
                <div class="navbar-start">
                    <a class="navbar-item has-text-weight-bold">
                        About
                    </a>
                    <a class="navbar-item has-text-weight-bold">
                        Pricing
                    </a>
                    <a class="navbar-item has-text-weight-bold">
                        FAQ
                    </a>
                    <a class="navbar-item has-text-weight-bold">
                        Contact Us
                    </a>
                </div>
            <div class="navbar-end">
            <div class="navbar-item">
                <div class="field is-grouped">
                    <p class="control">
                        <a class="button is-rounded has-background-grey-lighter has-text-weight-bold" href="">
                            <span>Login in</span>
                        </a>
                        
                    </p>
                    <p class="control">
                        <a class="button is-rounded has-background-grey-light has-text-weight-bold" href="">
                    
                        <span>Join now</span>
                        </a>
                    </p>
                                
                </div>
            </div>
            </div>
        </div>
      </nav>
</template>

<script>

export default {
  name: 'NavBar'
}
</script>

<style scoped>
    .navbar-item.is-mega {
    position: static;
}
.is-mega-menu-title {
      margin-bottom: 0;
      padding: .375rem 1rem;
}

.fa-circle {
    color: hsl(0, 0%, 71%);
}

.navbar-item{
    padding-top: 30px;
}

.navbar-start a:hover{
    
    border-top:2px solid purple;
}

.navbar-end a:hover{
    border:2px solid purple;
}
</style>

