<template>
  <div>
    <NavBar/>
    <br/>
    <h1>Ratatouille</h1>
    <h5>PLAT SPÉCIAL!</h5>
    <br/>
    <iframe width="1120" height="630" src="https://www.youtube.com/embed/XAw7wC3Ykh8"
    frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <br/>
    <br/>
    <h1>La cuisine française</h1>
    <br/>
    <div>
      <img alt="Vue logo" height="676" widht="530" src="../assets/Cocina00.png" />
      <div class="parrafo" style="text-align: justify;">
        <p>La cuisine française fait référence à divers styles gastronomiques dérivés de la tradition française. Elle a évolué au cours des siècles, suivant ainsi les changements sociaux et politiques du pays. Le Moyen Âge a vu le développement de somptueux banquets qui ont porté la gastronomie française à un niveau supérieur, avec une nourriture décorée et fortement assaisonnée par des chefs tel Guillaume Tirel.</p>
        <p>Au xviie siècle, les habitudes ont changé, avec une utilisation moins systématique des épices et avec le développement de l'utilisation des herbes aromatiques et de techniques raffinées, initiées par François Pierre de La Varenne et par d'autres dignitaires de Napoléon Bonaparte, comme Marie-Antoine Carême.</p>
      </div>
    </div>
    <br/>
    <h1>Ingrédients et préparation </h1>
    <div>
      <img alt="Vue logo" height="1076" widht="930" src="../assets/Rata00.png" />
    </div>
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
  $padding: 155px;

  .parrafo{
    padding-right: $padding;
    padding-left: $padding;
  }

  p {
    font-size: 1.5rem;
  }

</style>
