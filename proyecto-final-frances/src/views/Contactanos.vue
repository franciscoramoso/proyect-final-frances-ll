<template>
  <div>
    <NavBar />
    <br/>
    <h1>Contactez nous</h1>
    <div class="aboutUs">
      <b-form>
        <b-form-input type="text" required placeholder="Nom complet*"></b-form-input>
        <br/>
        <b-form-input type="email" required placeholder="Courrier électronique*"></b-form-input>
        <br/>
        <b-form-input type="number" placeholder="Numéro de téléphone"></b-form-input>
        <br/>
        <b-form-textarea
          required
          placeholder="Votre commentaire*..."
          rows="3"
          max-rows="6"
        ></b-form-textarea>
        <br/>
        <b-button block type="submit" variant="primary">Envoyer</b-button>
      </b-form>

    </div>



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
  .aboutUs{
      width: 100%;
      max-width: 630px;
      padding: 15px;
      margin: auto;
  }
</style>
