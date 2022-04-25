<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import AppHeader from './components/AppHeader.vue';
import Hero from './components/Hero.vue';

</script>

<template>
  <AppHeader/>
  <Hero title="More than just shorter links" />
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500;700&display=swap');

html {
  font-size: 18px;
}

#app {
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $color-neutral-grayishviolet;
}

.btn {
  color: #ffffff;
	background-color: $color-primary-cyan;
	border-radius: 2.3em;
  display: inline-block;
  cursor: pointer;
  font-size: 1em;
  font-weight: 700;
  padding: 0.7em 2.3em;
  text-decoration: none;
  &:hover {
    color: #ffffff;
	  background-color:#9be3e2;
}
}
</style>
