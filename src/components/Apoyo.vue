<template lang="html">
  <v-container class="fondo pt-12 pb-8" fluid>
    <v-container>
      <v-col cols="12">
        <v-row justify="center">

          <v-col cols="10">
            <h2 class="text-center">
              Clientes
            </h2>
            <v-row justify="center" align="center">
              <v-col cols="4" sm="3" :key="index" v-for="(n, index) in 7">
                <v-img
                height="5em"
                contain
                :src="require(`@/assets/clientes/cliente${n}.png`)"
                />
              </v-col>
            </v-row>
            <v-row justify="center">
              <v-col cols="7">
                <v-divider ></v-divider>
              </v-col>
            </v-row>
          </v-col>


          <v-col cols="10">
            <h2 class="text-center">
              Aliados
            </h2>
            <v-row justify="center" align="center">
              <v-col cols="3" sm="2" :key="index" v-for="(n, index) in 20">
                <v-img
                height="5em"
                contain
                :src="require(`@/assets/aliados/aliado${n}.png`)"
                />
              </v-col>
            </v-row>
            <v-row justify="center">
              <v-col cols="7">
                <v-divider ></v-divider>
              </v-col>
            </v-row>
          </v-col>


          <v-col cols="10">
            <h2 class="text-center">
              Aportantes
            </h2>
            <v-row justify="center" align="center">
              <v-col cols="3" sm="2" :key="index" v-for="(n, index) in 6">
                <v-img
                height="5em"
                contain
                :src="require(`@/assets/aportantes/aportante${n}.png`)"
                />
              </v-col>
            </v-row>
          </v-col>

        </v-row>
      </v-col>
    </v-container>
  </v-container>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
h2  {
  color: #00BDC7;
  font-size: 2.2em;
  font-weight: 700;
}
.fondo{
  background-color: white
}
</style>
