<template>
  <div id="nav" class="container mx-auto p-8">
    <router-link class="" to="/">Home</router-link> |
    <router-link class="" to="/about">About</router-link>
  </div>
  <router-view />
</template>

<script>
import "tailwindcss/tailwind.css";
export default {};
</script>

<style lang="scss">
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

a {
  font-weight: bold;
  color: #2c3e50;

  &.router-link-exact-active {
    @apply text-green-500;
  }
}
</style>
