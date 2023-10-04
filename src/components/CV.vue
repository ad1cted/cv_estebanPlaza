<template>
  <div class="body">
    <HeaderBar class="pdf-item"
               email="esteban.plaza.a@usach.cl"
               name="Esteban Isaias Plaza"
    />
    <Resume/>
    <Skills/>
    <Experience/>
    <Education/>
    <Hobbies/>
    <Final/>

  </div>
</template>

<script>

import Resume from "@/components/Resume.vue";
import Skills from "@/components/Skills";
import HeaderBar from "@/components/HeaderBar";
import Experience from "@/components/Experience";
import Education from "@/components/Education";
import Hobbies from "@/components/Hobbies";
import Final from "@/components/Final";

export default {
  name: 'CV',
  components: {
    Resume,
    Skills,
    HeaderBar,
    Experience,
    Education,
    Hobbies,
    Final,
  },
}
</script>



