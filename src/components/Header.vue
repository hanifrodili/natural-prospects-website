<template lang="pug">
.header
  v-row.ma-0
    v-col.pa-0(cols="12" md="8")
      .main-header
        div
          .main-heading 
            h1 Hanif Construction
          .main-description
            p Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam lectus erat consectetur eu sapien eget, rhoncus consectetur sem.
          div.d-flex
            a(href="/#projects")
              v-btn.primary-btn.mr-2 View our works
            a(:href="'https://wa.me/'+ phoneNum" target="_blank" )
              v-btn.primary-btn-outlined.mr-2 Get free quote
        .overlay
    v-col.pa-0(cols="12" md="4")
      .services
        h3.title Our Services
        v-row
          v-col(cols="3")
            img(:src="require('@/assets/img/brickwall.png')" width="100%" )
          v-col(cols="9")
            p.service-title Structural Construction
            p.service-desc Lorem ipsum dolor sit amet
        v-row
          v-col(cols="3")
            img(:src="require('@/assets/img/home.png')" width="100%" )
          v-col(cols="9")
            p.service-title Renovation
            p.service-desc Lorem ipsum dolor sit amet
        v-row
          v-col(cols="3")
            img(:src="require('@/assets/img/helmet.png')" width="100%" )
          v-col(cols="9")
            p.service-title Structural Repair
            p.service-desc Lorem ipsum dolor sit amet
        v-row
          v-col(cols="3")
            img(:src="require('@/assets/img/waterproof.png')" width="100%" )
          v-col(cols="9")
            p.service-title Waterproofing
            p.service-desc Lorem ipsum dolor sit amet
</template>

<script>
export default {
  name: 'Header',
  data: () => ({
    phoneNum: '60134714296'
  })
}
</script>

<style lang="css" scoped>
.main-header{
  padding: 111px 66px;
  background-image: url('https://picsum.photos/600/400');
  background-size: cover;
  height: 100%;
  position: relative;
  display: grid;
}
.main-header > div{
  height: fit-content;
  margin: auto;
}
.main-header .overlay{
  height: 100%;
  width: 100%;
  position: absolute;
  background-color: rgba(44, 44, 44, 0.8);
  inset: 0;
}
.main-heading{
  border-left: 10px solid var(--clr-primary);;
  padding-left: 16px!important;
  margin-bottom: 0px!important;
  max-width: 800px;
  position: relative;
  z-index: 1;
}
.main-heading h1{
  font-weight: 700;
  font-size: 64px;
  line-height: 1.1em;
  background-color: #000000;
  padding: 2px;
  color: white;
  display: inline;
  padding-left: 5px;
  padding-right: 5px;
}
.main-description{
  color: #fff;
  line-height: 1.6em;
  font-size: 22px !important;
  line-height: 1.6em;
  padding-top: 20px!important;
  padding-bottom: 20px!important;
  max-width: 800px;
  position: relative;
  z-index: 1;
}

.services{
  padding: 80px 40px;
  background-color: var(--clr-primary);;
  height: 100%;
}
.services > .title{
  font-weight: 700;
  font-size: 32px !important;
  line-height: 1.2em;
  margin-bottom: 23px;
}
.service-title{
  font-size: 18px;
  font-weight: 700;
  color: #2a2a2a!important;
  line-height: 1.4em;
  padding-bottom: 10px;
  margin-bottom: 0;
  margin-top: 15px;
}
.service-desc{
  font-weight: 300;
  color: white !important;
  line-height: 1.4em;
}

@media(max-width: 959px){
  .main-header{
    padding: 111px 30px;
    height: 100vh;
  }
  .main-heading h1{
    font-weight: 600;
    font-size: 48px;
  }
  .main-description{
    font-size: 18px !important;
  }
}

@media(max-width: 320px){
  .main-heading h1{
    font-weight: 600;
    font-size: 42px;
  }
}
</style>
