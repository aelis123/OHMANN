<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <div id="layout">
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Events</RouterLink> |
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>


  <RouterView />
  </div>
</template>

<style>
#layout {
font-family: Avenir, Arial, Helvetica, sans-serif;
-webkit-font-smoothing: antialiased;

text-align: center;
color: #2c3e50;  
}

nav {
  padding: 30px;
} 

nav a {
  font-weight: bold;  
  color: lightgrey;
}

nav a.router-link-exact-active {
  color: #2c3e50;
}

h2 {
  font-size: 20px;
}
</style>
