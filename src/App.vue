<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <router-view />
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Onest:wght@100..900&display=swap');

body {
  margin: 0;
  padding: 0;
  color: var(--color-secondary);
  font-family: "Onest", Avenir, Helvetica, Arial, sans-serif;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

:root {
  --color-bg: #001C1A;
  --color-primary: #CEFF00;
  --color-secondary: #FFF;
}
</style>