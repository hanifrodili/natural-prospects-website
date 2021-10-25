<template lang="pug">
.projects
  div
    h2.section-title.text-center Past Projects
    div.title-div.mx-auto
    v-row
      v-col(cols="12" md="4")
        img.project-img(src="https://picsum.photos/600/400" width="100%" )
        div.project-details
          p.title Project Title
          p.desc Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasell sed nibh dignissim, cursus tellus sit amet, ultrices mauris. 
      v-col(cols="12" md="4")
        img.project-img(src="https://picsum.photos/600/400" width="100%" )
        div.project-details
          p.title Project Title
          p.desc Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasell sed nibh dignissim, cursus tellus sit amet, ultrices mauris.
      v-col(cols="12" md="4")
        img.project-img(src="https://picsum.photos/600/400" width="100%" )
        div.project-details
          p.title Project Title
          p.desc Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasell sed nibh dignissim, cursus tellus sit amet, ultrices mauris.
</template>

<script>
export default {
  name: 'Projects'
}
</script>

<style lang="scss" scoped>
.projects{
  padding: 80px 20px;
}
.projects > div{
  max-width: 1080px;
  margin: auto;
}
.project-img{
  border-radius: 5px 5px 0 0;
}
.project-details{
  border: 1px solid #cecece;
  padding: 35px;
  border-radius: 0px 0px 5px 5px;
}
.project-details .title{
  font-weight: 700!important;
  font-size: 16px!important;
  line-height: 1.2em!important;
}
.project-details .desc{
  font-size: 15px;
  line-height: 1.8em;
}
</style>
