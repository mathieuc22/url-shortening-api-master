<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import AppHeader from './components/AppHeader.vue';
import Hero from './components/Hero.vue';
import Shorten from './components/Shorten.vue';

</script>

<template>
  <AppHeader/>
  <Hero title="More than just shorter links" />
  <Shorten/>
</template>

<style lang="scss">

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
	  background-color: lighten($color: $color-primary-cyan, $amount: 20%);
}
}
</style>
