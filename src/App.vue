<template>
  <v-app>
    <v-container class="pa-0" fluid>

      <Header/>
      <Graphic/>
      <Organizaciones/>
      <Lineas/>
      <Apoyo/>
      <Contacto/>

    </v-container>
  </v-app>
</template>

<script>
import Header from './components/Header'
import Graphic from './components/Graphic'
import Organizaciones from './components/Organizaciones'
import Lineas from './components/Lineas'
import Apoyo from './components/Apoyo'
import Contacto from './components/Contacto'

export default {
  name: 'App',

  components: {
    Header,
    Graphic,
    Organizaciones,
    Lineas,
    Apoyo,
    Contacto
  },

  data: () => ({
    //
  }),
};
</script>

<style media="screen">

</style>
