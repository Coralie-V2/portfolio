<template>
  <div class="container">
    <h1 class="row mt-5">2020 - The Hiking</h1>
    <hr class="row col-3">

    <div class="projet row my-5">
      <div class="texte col-12 col-md-8">
        <h2>Description du projet</h2>
        <p>Le projet "Hiking" est un site WordPress que j'ai réalisé durant ma deuxième année de MMI, je l'ai conçu grâce au thème AVADA et il est entièrement responsive. Je devais réaliser ce site grâce à une maquette graphique fournie.</p>
      </div>
      <div class="photo col-12">
        <img class="image-projet" src="static/img/hiking-pc.png" alt="page d'accueil hiking version pc">
      </div>
      <div class="texte col-12 col-md-8">
        <h2>Outils</h2>
        <p>WordPress (thème AVADA)</p>
      </div>
      <div class="texte col-12 col-md-8">
        <h2>Aperçu du travail</h2>
        <a href="https://hiking.coralievarrier.fr/">-> Lien vers le WordPress</a>
      </div>
    </div>



  </div>
</template>

<script>
export default {
  name: 'Hiking',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

.container .projet p{
  margin: 1.5rem 0;
}
hr{
  color: #dc3545;
  background-color: #dc3545;

}
.image-projet{
  margin-top: 2rem;
  max-width: 600px;
  margin-bottom: 5rem!important;

}

@media (max-width: 576px) {
  .image-projet{
    max-width: 400px;
  }
}
p{
  font-family: "Noto Sans", sans-serif;
}
.projet h2{
  font-weight: bold;
}


a{
  color: black;
  display: inline;
}
a:hover{
  color: #dc3545;
}
</style>
