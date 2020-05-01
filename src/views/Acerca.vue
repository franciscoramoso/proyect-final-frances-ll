<template>
  <div>
    <NavBar />
    <br/>
    <h1>Près de nous</h1>
    <br/>
    <br/>
    <b-row class="text-center">
      <b-col cols="1"></b-col>

      <b-col md="auto">
        <img alt="Paco y Pinolo" height="576" widht="530" src="../assets/us00.jpg" />
      </b-col>

      <b-col cols="6">
        <br/>
        <br/>
        <p>Nous sommes un couple d'ingénieurs mexicains à la recherche du rêve européen.</p>

        <p>Nous avons décidé de collaborer avec nos compétences pour le projet final de frances ll.</p>
        <br/>
        <br/>
        <p>
          Francisco Ramos <br/>
          - Ingénieur systèmes informatiques
        </p>

        <p>
          Jose Dominguez <br/>
          - Ingénieur industriel
        </p>
      </b-col>
    </b-row>


    <br/>
  </div>

</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";

export default {
  name: "Inicio",
  components: {
    NavBar
  }
};
</script>

<style scoped lang="scss">
  p {
    font-size: 1.5rem;
  }
</style>
