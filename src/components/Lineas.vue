<template lang="html">
  <v-container fluid class="fondo py-8">

    <v-container>
      <v-row justify="center" align="center">
        <v-col cols="10">
          <h2 class="text-center">Lineas de trabajo</h2>
        </v-col>

        <v-col cols="10">

          <v-expansion-panels>
            <v-expansion-panel>
              <v-expansion-panel-header>Comunidades sostenibles</v-expansion-panel-header>
              <v-expansion-panel-content>
                <li>
                  <v-icon color="#009f95">mdi-circle-small</v-icon>Apoyo al trabajo decente y al crecimiento económico (empoderamiento de género, capacitación y emprendimientos sostenibles).
                </li>
                <li>
                  <v-icon color="#009f95">mdi-circle-small</v-icon>Educación para la sustentabilidad
                </li>
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel>
              <v-expansion-panel-header>Empresas sostenibles</v-expansion-panel-header>
              <v-expansion-panel-content>
                <li>
                  <v-icon color="#009f95">mdi-circle-small</v-icon> Compensación ambiental y economía circular (PSA-CSA, REP)
                </li>
                <li>
                  <v-icon color="#009f95">mdi-circle-small</v-icon>Compensación, verificación y monitoreo de huella de carbono e hídrica
                </li>
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel>
              <v-expansion-panel-header>Conservación de Ecosistemas</v-expansion-panel-header>
              <v-expansion-panel-content>
                <li>
                  <v-icon color="#009f95">mdi-circle-small</v-icon>Conservación, manejo, y monitoreo de ecosistemas
                </li>
                <li>
                  <v-icon color="#009f95">mdi-circle-small</v-icon>Restauración y protección participativa de servicios ecosistémicos
                </li>
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel>
              <v-expansion-panel-header>Alianzas para la sostenibilidad</v-expansion-panel-header>
              <v-expansion-panel-content>
                <li>
                  <v-icon color="#009f95">mdi-circle-small</v-icon>Comunitarias, institucionales y empresariales
                </li>
                <li>
                  <v-icon color="#009f95">mdi-circle-small</v-icon>Gestión interinstitucional y comunitaria para el desarrollo económico sustentable
                </li>
                <li>
                  <v-icon color="#009f95">mdi-circle-small</v-icon>Gestión del territorio (planificación y gobernanza local)
                </li>
              </v-expansion-panel-content>
            </v-expansion-panel>
          </v-expansion-panels>

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
  background-color: #e6e7e8
}
h2  {
  font-size: 2.2em;
  font-weight: 700;
  color: #c6cc38
}
li{
  padding-bottom: 1em
}
.v-expansion-panel-header{
  font-weight: 600;
  font-size: 1.2em;
}
</style>
