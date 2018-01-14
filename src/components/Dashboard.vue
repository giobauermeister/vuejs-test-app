<template>
  <v-app id="dashboard">
    <v-toolbar color="indigo" dark fixed app>
      <v-toolbar-title>
        <h1>Employee Manager</h1>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <img src="../assets/logo-ff.png" width="100px" alt="">
    </v-toolbar>

    <v-card id="card">
    <v-card-title>
      <h2>Funcionários Registrados</h2>         
    </v-card-title>
    <v-list two-line>
      <v-list-tile-content>
        <v-list-tile-title >Giovanni Bauermeister Santana</v-list-tile-title>
        <v-list-tile-sub-title >Analista de Desenvolvimento em Eletrônica</v-list-tile-sub-title>
      </v-list-tile-content>
    </v-list>
  </v-card>
      
  </v-app>
</template>

<script>
export default {
  name: "Dashboard",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#card {
  margin-top: 75px;
  margin-left: 20px;
  margin-right: 20px;
}
</style>
