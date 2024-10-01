<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header class="header">
    <img alt="Vue logo" class="logo" src="./assets/kirbo.png" width="125" height="125" />
    <div class="wrapper">
      <HelloWorld msg="Kirbo" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
.header {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}


@media (min-width: 1024px) {
  header {
    display:flex;
    place-items: center;
  }

  .logo {
    margin: 0 0 0 0;
  }
}
</style>
