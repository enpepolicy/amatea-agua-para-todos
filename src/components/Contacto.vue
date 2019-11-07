<template lang="html">
  <v-container class="fondo" fluid id="contacto">
    <v-container>
      <v-row justify="center">
        <v-col cols="10">
          <h2 class="">Contáctanos:</h2>
        </v-col>

        <v-col cols="5">
          <h3>NATALIA E. HINCAPIE</h3>
          <p>Coordinadora comercial<br>Cel: 317-6384173</p>
        </v-col>
        <v-col cols="5">
          <h3>SANTIAGO SIERRA</h3>
          <p>Coordinador científico<br>Cel: 317-6384173</p>
        </v-col>
        <v-col cols="5">
          <h3>JOAQUÍN NAVIA</h3>
          <p>Director del proyecto<br>Cel: 317-4011876</p>
        </v-col>
        <v-col cols="5">
          <h3>ANDRÉS SARMIENTO</h3>
          <p>Coordinador operativo<br>Cel: 317-4011876</p>
        </v-col>

        <v-col cols="10">
          <v-row justify="center" class="pt-1">
            <v-btn
            fab
            outlined
            href="https://www.facebook.com/aguaparatodoscolombia/"
            target="_blank"
            color="white"
            class="mx-9 social"
            large
            >
              <v-icon size="45px">mdi-facebook</v-icon>
            </v-btn>
            <v-btn
            fab
            outlined
            href="https://www.instagram.com/aguaparatodoscolombia/"
            target="_blank"
            color="white"
            class="mx-9 social"
            large
            >
              <v-icon size="45px">mdi-instagram</v-icon>
            </v-btn>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </v-container>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
.fondo{
  background-color: #c6cc38
}
h2  {
  color: #fff;
  font-size: 2.2em;
  font-weight: 700;
  text-align: center
}
h3{
  font-size: 1em;
  font-weight: 800;
  text-align: center

}
p{
  font-size: 0.8em;
  text-align: center;
}
</style>
