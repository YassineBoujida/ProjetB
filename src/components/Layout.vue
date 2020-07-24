<template>
    <div>
     <NavBar />
     <Section1 />
     <Section2 />
     <Section3 />
     <Section4 />
     <Section5 />
     <Section6 />
     <Section7 />
     <Footer /> 
    </div>
</template>

<script>

import NavBar from "./global_components/NavBar";
import Section1 from "@/views/Section1";
import Section2 from "@/views/Section2";
import Section3 from "@/views/Section3";
import Section4 from "@/views/Section4";
import Section5 from "@/views/Section5";
import Section6 from "@/views/Section6";
import Section7 from "@/views/Section7";
import Footer from "@/views/FooterView";

export default {
  name: 'Layout',
  components : {
     NavBar, Section1, Section2, Section3, Section4, Section5, Section6, Section7, Footer
  }
}
</script>


<style scoped>




</style>
