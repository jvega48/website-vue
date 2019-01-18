<template>
  <div class="home">
    <Header/>
    <SectionOne/>
    <SectionTwo/>
    <SectionThree/>
    <SectionFour/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import SectionOne from "@/components/SectionOne.vue";
import SectionTwo from "@/components/SectionTwo.vue";
import SectionThree from "@/components/SectionThree.vue";
import SectionFour from "@/components/SectionFour.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "home",
  components: {
    Header,
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
    Footer
  }
};
</script>
