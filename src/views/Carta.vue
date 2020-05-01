<template>
  <div>
    <NavBar />
    <br/>
    <h1>Menu</h1>
    <div>
      <img alt="Vue logo" height="676" widht="530" src="../assets/Menu00.jpeg" />
      <img alt="Vue logo" height="676" widht="530" src="../assets/Menu01.jpeg" />
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


</style>
