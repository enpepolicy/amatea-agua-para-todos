<template lang="html">
  <v-container class=" pt-0 pb-8 " fluid>
    <v-row>
    <v-container class="fondo-nosotros py-6 mb-12 " fluid>
      <v-container>
        <v-row justify="center">
          <v-col cols="12" sm="8">

            <h1 class="white--text">
              "Somos la unión de 3 ONG Vallecaucanas, en la búsqueda de unir el sector público y privado para comenzar el verdadero cambio ambiental en nuestra región."
            </h1>

          </v-col>
        </v-row>
      </v-container>
    </v-container>
    </v-row>

    <v-row justify="center">
      <v-col cols="10">
        <v-container>
          <v-row justify="space-around" align="center" class="pb-6">
            <v-col cols="12" sm="4">
              <v-img
              :src="require('@/assets/nosotros/amatea.png')"
              />
            </v-col>
            <v-col cols="12" sm="7">
              <p class="text-center">
                Amatea contribuye a la armonía del ser y la naturaleza. Apoyan empresas en temas de restauración y proyectos de compensación y manejo sustentable de bienes y servicios a la vez que se trabaja en la reconexión de las personas con sus ciclos naturales.
              </p>
            </v-col>
            <v-col cols="7">
              <v-divider ></v-divider>
            </v-col>
          </v-row>
        </v-container>

        <v-container v-if="$vuetify.breakpoint.smAndDown">
          <v-row justify="space-around" align="center" class="pb-6">
            <v-col cols="12" sm="4">
              <v-img
              :src="require('@/assets/nosotros/biodiversa.png')"
              />
            </v-col>
            <v-col cols="12" sm="7">
              <p class="text-center">
                Biodiversa es una organización dedicada al conocimiento, manejo y conservación de la biodiversidad para el desarrollo local y regional sostenible
              </p>
            </v-col>

            <v-col cols="7">
              <v-divider ></v-divider>
            </v-col>

          </v-row>
        </v-container>

        <v-container  v-if="$vuetify.breakpoint.mdAndUp">
          <v-row justify="space-around" align="center" class="pb-6">
            <v-col cols="12" sm="7">
              <p class="text-center">
                Biodiversa es una organización dedicada al conocimiento, manejo y conservación de la biodiversidad para el desarrollo local y regional sostenible
              </p>
            </v-col>
            <v-col cols="12" sm="4">
              <v-img
              :src="require('@/assets/nosotros/biodiversa.png')"
              />
            </v-col>

            <v-col cols="7">
              <v-divider ></v-divider>
            </v-col>

          </v-row>
        </v-container>

        <v-container>
          <v-row justify="space-around" align="center">
            <v-col cols="12" sm="4">
              <v-img
              :src="require('@/assets/nosotros/ecovida.png')"
              />
            </v-col>
            <v-col cols="12" sm="7">
              <p class="text-center">
                Construye futuro conectando personas y empresas para la restauración del entorno natural. Provee herramientas para resolver situaciones que afectan las sostenibilidad de los negocios, la sustentabilidad de la vida y el equilibrio ecológico

              </p>
            </v-col>
          </v-row>
        </v-container>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
.fondo-nosotros{
  background-color: #009F95
}
h1{
  font-size: 2.1em;
  text-align: center;
}
p{
  font-size: 1.2em;
  font-weight: 500;
  color: #009F95;
}
</style>
