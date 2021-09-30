<template>
  <div class="home">

    <div id="font">
      <div id="imagine"> Imagination & Creation </div>

      <h1>CRÉATION DE SITE WEB & FORMATION</h1>
      <p class="desc"> Quel que soit votre projet nous discutons ensemble pour trouver des solutions adaptées à vos besoins. Nous vous accompagnons dans la digitalisation de votre activité. Nous pouvons nous occuper de la création, de la refonte et des ajouts de fonctionnalités avancées pour votre site internet. Vous serez accompagné, formé et guidé étape par étape pour la réalisation de votre application web.</p>

      <div class="desc">  
       <p> <span class="contact"> CONTACT </span>  <span class="portfolio"> PORTFOLIO </span> </p>
      </div>
        
    </div>



    <HomeC msg="Accueil"/>
  </div>
</template>

<style scoped>
.portfolio {
    background-color: white;
}
.contact {
    border: 2px solid black;
}
span {
    padding: 15px;
    border-radius: 50px;
    margin-left: 70px;
    padding-left: 50px;
    padding-right: 50px;
}
.desc {
    max-width: 790px;
    text-align: justify;
    margin: auto;
    display: flex;
    flex-direction: column;
    align-items: center;
}
div#imagine {
    background-color: blue;
    color: white;
    width: 136px;
    margin: auto;
    font-size: 12px;
    padding: 6px;
    font-weight: bold;
}
div#font {
    background-image: url(../assets/clean-slider-2-1-e1588935449772.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 523px;
    display: flex;
    flex-direction: column;
}
</style>

<script>
// @ is an alias to /src
import HomeC from '@/components/HomeC.vue'

export default {
  name: 'Home',
  components: {
    HomeC
  }
}
</script>
