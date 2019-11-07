<template lang="html">
  <v-container fluid class="fondo pb-12">
    <v-container>
      <v-toolbar

      color="transparent"
      flat
      dark
      >
        <v-container>
          <v-row justify="end">
            <v-col cols="6" md="4">
              <v-btn
              href="#contacto"
              large
              color="#00BDC7"
              class="margin-button"
              block
              >
                <span >Contàctanos</span>
              </v-btn>
            </v-col>
          </v-row>
        </v-container>


      </v-toolbar>
      <v-img
      :src="require('../assets/territorios.png')"
      />
    </v-container>
  </v-container>

</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
@media only screen and (min-width : 961px){
  .margin-button{
    margin-top: 15em
  }
}
@media only screen and (max-width : 960px){
  .margin-button{
    margin-top: 3em
  }
}
.fondo{
  // background-color: #f
}
</style>
