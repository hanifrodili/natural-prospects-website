<template lang="pug">
  .construction
    page-header
    about
    projects(id="projects")
    testimoni
    banner
    page-footer
</template>
<script>
import PageHeader from '@/components/Header.vue'
import About from '@/components/About.vue'
import Projects from '@/components/Projects.vue'
import Testimoni from '@/components/Testimoni.vue'
import Banner from '@/components/CTABanner.vue'
import PageFooter from '@/components/Footer.vue'
export default {
  name: "Construction",
  components: {
    PageHeader,
    About,
    Projects,
    Testimoni,
    Banner,
    PageFooter
  }
}
</script>
<style scoped></style>
