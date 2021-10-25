<template lang="pug">
.testimoni
  div
    h2.section-title.text-center Client Testimonials
    div.title-div.mx-auto
    v-row
      v-col(cols="12" md="4")
        div.testimoni-details
          p.text
            span(style="font-size: 20px") “ 
            | Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasell sed nibh dignissim, cursus tellus sit amet, ultrices mauris
            span(style="font-size: 20px")  ”
          p.client client a
      v-col(cols="12" md="4")
        div.testimoni-details
          p.text 
            span(style="font-size: 20px") “ 
            | Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasell sed nibh dignissim, cursus tellus sit amet, ultrices mauris
            span(style="font-size: 20px")  ”
          p.client client b
      v-col(cols="12" md="4")
        div.testimoni-details
          p.text
            span(style="font-size: 20px") “ 
            | Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasell sed nibh dignissim, cursus tellus sit amet, ultrices mauris
            span(style="font-size: 20px")  ”
          p.client client c
</template>

<script>
export default {
  name: 'Testimoni'
}
</script>

<style lang="scss" scoped>
.testimoni{
  padding: 80px 20px;
}
.testimoni > div{
  max-width: 1080px;
  margin: auto;
}
.testimoni-details{
  border: 1px solid #cecece;
  padding: 35px;
  border-radius: 5px;
}
.testimoni-details .client{
  font-weight: 500!important;
  font-size: 16px!important;
  line-height: 1.2em!important;
  text-align: center;
  text-transform: uppercase;
}
.testimoni-details .text{
  font-size: 15px;
  line-height: 1.8em;
  text-align: center;
}
</style>
