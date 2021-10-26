<template lang="pug">
.about
  v-row.ma-0
    v-col.pa-0(cols="12" md="4")
      div.about-img
    v-col.pa-0(cols="12" md="8")
      div.about-content
        h2.section-title About us
        div.title-div
        p.section-text We are a G5 Bumiputra Contractor experienced in Civil, Structural and Marine Construction, Renovation, Forensic Engineering, Structural Repair, Waterproofing, Slope Repair, Roadworks, Soil Investigation, Steel Works, Mechanical & Electrical Works
      v-row.w-10.ma-0
        v-col.stat(cols="6")
          div.number 25
          div.text Years Established
        v-col.stat(cols="6")
          div.number 100
          div.text Projects Completed
</template>

<script>
export default {
  name: 'About'
}
</script>

<style lang="css" scoped>
/* .about{
  padding-top: 80px
} */
.about-img{
  background-image: url('https://picsum.photos/600/800');
  background-size: cover;
  height: 100%;
}
.about-content{
  padding: 80px 50px;
}
.stat{
  padding: 30px 0;
  text-align: center;
}
.stat:nth-of-type(1){
  background-color: var(--clr-primary);;
  color: #2a2a2a;
}
.stat:nth-of-type(2){
  background-color: #2a2a2a;
  color: #fff;
}
.stat .number{
  font-weight: 700;
  font-size: 42px;
  line-height: 70px;
}
.stat .text{
  font-weight: 700;
  text-transform: uppercase;
  font-size: 12px;
  letter-spacing: 2px;
  line-height: 1.6em;
}

@media(max-width: 959px){
  .stat .number{
    font-weight: 700;
    font-size: 38px;
    line-height: 70px;
  }
  .stat .text{
    font-weight: 700;
    text-transform: uppercase;
    font-size: 9px;
    letter-spacing: 2px;
    line-height: 1.6em;
  }
  .about-img{
    display: none;
  }
  .about-content{
    padding: 80px 35px;
  }
}
</style>
