<template>
  <div id="app" class="bg-[#93b1a67e]">
    <!-- <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav> -->
    <router-view />
  </div>
</template>

<style>
/* nav a {
  font-weight: bold;
  color: #2c3e50;
} */

nav a.router-link-exact-active {
  color: #42b983;
}

/* .body {
  background-image: url('../src/assets/bg.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
} */

/* * {
  border: 1px solid red;
} */
</style>
