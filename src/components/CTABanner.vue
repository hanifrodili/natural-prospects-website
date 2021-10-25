<template lang="pug">
.banner
  div
    h1.mb-4 Get a Quote For Your Project
    a(:href="'https://wa.me/'+ phoneNum" target="_blank" )
      v-btn.primary-btn Free Quote
</template>

<script>
export default {
  name: 'Banner',
  data: () => ({
    phoneNum: '60134714296'
  })
}
</script>

<style lang="css" scoped>
.banner{
  background-color: #cecece;
  padding: 45px 0;
}
.banner > div{
  margin: auto;
  max-width: 1080px;
  text-align: center;
}
.banner > div h1{
  font-weight: 700;
  font-size: 42px;
  line-height: 1.2em;
}

@media(max-width: 959px){
  .banner{
    padding: 45px 20px;
  }
  .banner > div h1{
    font-weight: 700;
    font-size: 38px;
  }
}
</style>
