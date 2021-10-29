<template>
  <div id="app">
    <div id="nav">
      <h2>Dev_Marienoir</h2>
      <!-- <img alt="Vue logo" src="\src\assets\logo.png"> -->
      <div class="links">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/contact">Contact Us</router-link>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lobster&family=Nunito+Sans:wght@200;400;600&family=Poppins:wght@400;500&display=swap");
#app {
  font-family: "Poppins", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: justify;
  /* max-width: 1440px;
  margin: auto; */
  color: rgb(48, 45, 45);
}
h2{
  font-family: "Lobster", cursive;
  font-size: 25px;
}
#nav {
  padding:10px 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

#nav a {
  font-weight: bold;
  color: rgb(228, 39, 39);
  margin: 0 30px 0 30px;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: rgb(248, 124, 124);
  border-bottom: 3px solid;
}
</style>
