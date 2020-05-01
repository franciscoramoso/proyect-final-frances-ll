<template>
  <div>
    <NavBar />
    <br/>
    <h1>Casa pinolo<small>By Paco</small></h1>
    <br/>
    <iframe width="1120" height="630" src="https://www.youtube.com/embed/MuWIQif1uto" 
    frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <br/>
    <br/>
    <h1>Restaurant</h1>
    <div class="parrafo" style="text-align: justify;">
      <p>La nourriture mexicaine possède l'une des gastronomies les plus riches du monde, mais malheureusement et en tant que fier mexicain, je peux dire qu'en dehors du pays, il perd non seulement sa saveur exquise; mais aussi son essence, une essence non seulement pleine de couleurs, épicée, sucrée et même les deux à la fois (délicieuse, croyez-le ou non) mais aussi pleine d'histoire et de culture. Où un seul plat ne laissera pas seulement votre palais sans voix, mais il vous racontera également une histoire, une fable ou certains auront même une sorte de "légende". Comme les célèbres chiles en nogada originaires de Puebla, où l'histoire de leur création peut aller du conte le plus romantique sur les trois copines de trois soldats de l'armée, à une histoire ennuyeuse où les récoltes de l'époque étaient simplement utilisées pour réaliser un plat commémorant l'indépendance du Mexique, subtil? Bien sûr, mais incroyable? Je ne crois pas.</p>
      <p>Et c'est là que je vous demande, aimeriez-vous découvrir toute cette magie dans votre bouche, sans avoir besoin de voyager de l'autre côté de la planète? C'est vrai, comme si le Disneyland de la nourriture était dans votre ville. Je vais vous donner l'occasion de vous asseoir à une table et de demander des tacos, qui ont vraiment le goût de tacos, avec de délicieuses sauces, rouges et vertes; Et comme ce n'est pas une bière très froide, c'est plus que je suis si heureux que vous ayez cette expérience que si vous mangez avec un chapeau je ne serai pas offensé.</p>
      <p>Je veux apporter autant que possible un "vrai" restaurant mexicain, au revoir au restaurant classique de style mexicain avec une méthodologie de restauration rapide avec des plats inventés et bonjour à CASA PINOLO, où quiconque nous rend visite se trouve au Mexique ou même à la maison ( Mexique) si vous vous en éloignez soit pour une nouvelle aventure soit pour le destin de la vie, ici je vous assure que vous trouverez un bout de votre terre.</p>
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
  $padding: 155px;

  .parrafo{
    padding-right: $padding;
    padding-left: $padding;
  }

  p {
    font-size: 1.5rem;
  }

  small{
    font-size: 1rem;
  }

</style>
