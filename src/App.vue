<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header> -->

  <RouterView />
  <!-- <div class="container"> 

  <div class="grid grid-cols-4 gap-4">
    <p>lorem</p>
    <p>lorem</p>
    <p>lorem</p>
    <p>lorem</p>
    <p>lorem</p>
    <p>lorem</p>
    <p>lorem</p>
    <p>lorem</p>
  </div>
  </div> -->
</template>
<style>

body {

}

</style>