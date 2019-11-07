<template lang="html">
  <v-container fluid class="fondo">
    <v-container>
    <v-row>
      <v-col cols="12">
        <v-row justify="center">
          <v-img
          contain
          max-height="20em"
          :src="require('../assets/logo.png')"
          />
          <v-carousel
          light
          :show-arrows="false"
          hide-delimiter-background
          height="false">
            <v-carousel-item
            v-for="frase in frases"
            :key="frase"
            >
              <v-row
                class="fill-height"
                align="center"
                justify="center"
              >
                <v-col cols="10" sm="6">
                  <p class="text-center mt-5 mb-12">
                    <span class="azul">"</span> {{frase}} <span class="azul">"</span>
                  </p>
                </v-col>
              </v-row>
            </v-carousel-item>
          </v-carousel>
        </v-row>
      </v-col>
    </v-row>
    </v-container>
  </v-container>
</template>

<script>
  export default {
    data () {
      return {
        frases: [
          'Trabajamos por reducir el riesgo de desabastecimiento actual y a futuro del agua de uso doméstico e industrial',
          'Trabajamos por recuperar las áreas deforestadas de ecosistemas estratégicos y áreas protegidas',
          'Trabajamos con las comunidades rurales vulnerables por su desarrollo social, económico y ambiental',
          'Mejorar la conectividad ecosistémica en el corredor biológico entre PNN Farallones y PNN Tatama. Para disminuir la fragmentación y el riesgo de extinción local de especies'
        ],
      }
    },
  }
</script>

<style lang="css" scoped>
.fondo{
  background-color: #e6e7e8
}
p{
  font-size: 1.6em;
  font-weight: 700;
  color: #c6cc38
}
.azul, .v-btn{
  color: #45b1af !important
}
</style>
