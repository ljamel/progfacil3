<template>

  <div id="nav">
    <div class="logo" alt="Logo"/>
    <router-link to="/">Accueil</router-link> 
    <router-link to="/services">Services</router-link> 
    <router-link to="/tutos">Tutos</router-link> 
    <router-link to="/portfolio">Portfolio</router-link>   
    <router-link to="/about">a propos</router-link> 
    <router-link to="/contact">Contact</router-link> 
   
    
  </div>
  <router-view/>
</template>



<style>
.logo{
  width: 88px;
  background-image: url(assets/logoprogfacil.png);
  background-repeat: no-repeat;
  background-size: cover;
  height: 40px;
  
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

#nav a {
  text-decoration: none;
}
</style>
