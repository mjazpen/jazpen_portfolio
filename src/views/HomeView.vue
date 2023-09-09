<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import AboutView from './AboutView.vue'
import HeroView from './HeroView.vue'
</script>

<template>
  <main>
    <HeroView />
    <AboutView />
  </main>
</template>
<style>
:root{
  --dark-color: #4B4D4E;
  --light-color: #F6F7EA;
}

.about{
  background: radial-gradient(178.89% 127.53% at 104.72% 108.01%, #0A3045 0%, #120224 100%);
  min-height: 100vh;
}

svg{
  cursor: pointer;
}

  /* Define the animation */
  @keyframes rotate {
    from {
      transform: rotate(0deg);
    }
    to {
      transform: rotate(360deg);
    }
  }
  @keyframes rotate_reverse {
    from {
      transform: rotate(360deg);
    }
    to {
      transform: rotate(0deg);
    }
  }

  /* Apply the animation to the image */
  #avatar #lg1 {
    animation: rotate 90s linear infinite;
    /* You can adjust the speed by changing the '1s' duration */
    transform-origin: center;
  }
  #avatar #lg2 {
    animation: rotate_reverse 100s linear infinite;
    /* You can adjust the speed by changing the '1s' duration */
    transform-origin: center;
  }
  #avatar #med1 {
    animation: rotate 100s linear infinite;
    /* You can adjust the speed by changing the '1s' duration */
    transform-origin: center;
  }
  #avatar #med2 {
    animation: rotate_reverse 150s linear infinite;
    /* You can adjust the speed by changing the '1s' duration */
    transform-origin: center;
  }
  #avatar #sm1 {
    animation: rotate 30s linear infinite;
    /* You can adjust the speed by changing the '1s' duration */
    transform-origin: center;
  }
  #avatar #sm2 {
    animation: rotate 40s linear infinite;
    /* You can adjust the speed by changing the '1s' duration */
    transform-origin: center;
  }

</style>