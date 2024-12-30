<template>

  <header>

    <div class="logo">
      <img class="header-image" src="./image/vélo bleu.png" alt="vélo bleu">
    </div>

    <div class="blocD">
      <h4>Vélo !</h4>
      <h4>Photos !</h4>
      <h4>Aventures !</h4>
    </div>

  </header>

  <H1>LES SORTIES VELO DE FELIX</H1>
  <h2>Ceci c'est pour voir</h2>
  <h3>C'est super le vélo, du coup je raconte mes aventures de vélo.</h3>

  <p>Coucou c'est moi et je fais un cours de code avec Geoffrey</p>
  <div class="geoffrey">
    <p>"Je confirme que c'est un super site !"</p>
    <p class="Gras">Le Gorafi</p>
  </div>

  <footer>
    <div class="cat1">
      <h5>Me contacter:</h5>
      <h5>Instagram :</h5>
      <h5>Github :</h5>
      <h5>Mail :</h5>
    </div>
    <div><img src="./image/Encore-un vélo jaune.png" alt="vélo jaune"></div>

    <div class="cat2">
      <h5>Me contacter:</h5>
      <h5>Instagram :</h5>
      <h5>Github :</h5>
      <h5>Mail :</h5>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');

@import url('https://fonts.googleapis.com/css2?family=League+Spartan:wght@100..900&family=Nunito:ital,wght@0,200..1000;1,200..1000&display=swap');

@font-face {
  font-family: 'MoreSugar-Regular';
  src: url('image/MoreSugar-Regular.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

h1 {
  font-family: 'League Spartan', sans-serif;
  font-size: 4rem;
}

h2 {
  font-family: Telegraf, sans-serif;
}

h3 {
  margin: 40px 0 0;
  font-family: Nunito, sans-serif;
}

p {
  font-family: Nunito, sans-serif;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 10px;
}

a {
  color: #42b983;
}

header {
  display: flex;
  align-items: center;
  background-color: #ffde59;
  flex-direction: row;
}

img {
  margin-left: 20px;
  height: 85px;
}

footer {
  background-color: #2c3e50;
  display: flex;
  align-items: center;
  justify-content: space-around;
}

.logo {
  margin-right: 20px;
}



.blocD {
  background-color: #ffde59;

  font-size: 30px;
  font-family: 'MoreSugar-Regular';

  color: #2c3e50;

  display: flex;
  gap: 20px;
  /* Espace entre les éléments de texte */
  flex-grow: 1;
  /* Permet au menu de prendre tout l'espace disponible */
  justify-content: center;
  /* Centre les éléments de texte */
}

.blocD h4 {
  margin: 3%;
}





.cat1 .cat2 {
  display: flex;
  flex-direction: column;
}

.geoffrey {
  font-size: 24px;
  /* Taille de police plus grande */
  color: #FF5733;
  /* Couleur vive */

  text-align: center;
  /* Centrer le texte */
  animation: shake 0.5s infinite;
  /* Animation de secousse */
  background-color: #FFFF00;
  /* Fond jaune */
  border: 2px dashed #FF5733;
  /* Bordure en pointillés */
  padding: 20px;
  /* Espacement intérieur */
  margin: 20px;
  /* Espacement extérieur */
  border-radius: 15px;
  /* Coins arrondis */
  box-shadow: 0 0 20px rgba(255, 87, 51, 0.5);
  /* Ombre portée */

}

.Gras {
  font-weight: bold;
  color: black;
}

@keyframes shake {
  0% {
    transform: translate(1px, 1px);
  }

  25% {
    transform: translate(-1px, -2px);
  }

  50% {
    transform: translate(-3px, 0px);
  }

  75% {
    transform: translate(3px, 2px);
  }

  100% {
    transform: translate(1px, -1px);
  }
}
</style>