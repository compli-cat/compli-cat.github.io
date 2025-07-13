<template>
  <div class="px-4">
    <nav class="sticky top-0 z-50 rounded-xl">
      <router-link active-class="active" to="/"       >Home</router-link> |
      <router-link active-class="active" to="/about"  >About</router-link> |
      <router-link active-class="active" to="/games"  >Games</router-link> |
      <router-link active-class="active" to="/web"    >Web</router-link> |
      <router-link active-class="active" to="/contact">Contact</router-link>
    </nav>
    <router-view/>
  </div>
  
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}
</style>
