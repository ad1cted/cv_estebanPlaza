<template>
  <div class="body">
    <HeaderBar class="pdf-item"
               email="esteban.plaza.a@usach.cl"
               name="Esteban Isaias Plaza"
    />
    <Summary/>
    <Skills/>
    <Experience/>
    <Education/>
    <Hobbies/>
    <Certifications/>
    <Footer/>

  </div>
</template>

<script>

import Summary from "@/components/Summary";
import Skills from "@/components/Skills";
import HeaderBar from "@/components/HeaderBar";
import Experience from "@/components/Experience";
import Education from "@/components/Education";
import Hobbies from "@/components/Hobbies";
import Footer from "@/components/Footer";
import Certifications from "@/components/Certifications";

export default {
  name: 'CV',
  components: {
    Summary,
    Skills,
    HeaderBar,
    Experience,
    Education,
    Hobbies,
    Footer,
    Certifications
  },
}
</script>



