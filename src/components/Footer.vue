<template lang="pug">
.footer
   v-row
      v-col(cols="12" md="10")
        v-row
          v-col.text-center(cols="12")
            p.mb-0 © 2021 Hanif Construction. All rights reserved.
      v-col(cols="12" md="2")
        v-row.mx-auto(style="width:fit-content")
          v-col.text-center(cols="6")
            a(href="#" )
              v-icon.socmed-icon mdi-facebook
          v-col.text-center(cols="6")
            a(href="#" )
              v-icon.socmed-icon mdi-whatsapp
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style lang="css" scoped>
.footer > .row{
  max-width: 1080px;
  margin: auto;
}
.footer{
  background-color: var(--clr-primary);
  color: black;
  padding: 30px 0;
}
.footer .v-icon{
  color: black;
}
.footer p{
  width: fit-content;
  text-align: left;
}

@media (max-width: 959px){
  .footer p{
    width: 200px;
    margin: auto;
    text-align: center;
  }
}
</style>
