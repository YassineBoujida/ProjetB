<template>
  <div id="app">
    <Layout />
  </div>
</template>

<script>

import Layout from "@/components/Layout";
export default {

  name : "app",
  components:{
    Layout
  }
  
}
</script>
<style>
.parent {
    position: relative;
    top: 0;
    left: 0;
  }

  .about {
   color:purple
}

.paragraph{
    color:#637D9C
}

a.paragraph2{
    color:purple
}

.card, .card2{
    background-color:#554E63 !important
}

.since-paragraph{
    border-left: 2px solid gray;
}

.content2 figure{
      margin:0!important;
  }

  .is-horizontal-center {
    justify-content: center;
    }

.box:hover{ 
    box-shadow: 1px 8px 20px grey;
   -webkit-transition:  box-shadow .4s ease-in;
 }

</style>
