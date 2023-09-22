<template>
  <v-app>
    <v-main class="center">
      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({

  }),
}
</script>
<style coped>
.center {
  background-color: hsla(225, 100%, 94%, 1);
  width: 100vw;
  height: 100vh;
  background: url(./assets/pattern-background-mobile.svg);
  background-repeat: no-repeat;
  background-color: #E0E8FF;
  background-size: 100%;
  background-position-y: -20rem;
  display: flex;
  justify-content: center;
  align-items: center;
}

body {}

@media (min-width: 768px) {

  v-app {
    background: url(./assets/pattern-background-desktop.svg);
    background-repeat: no-repeat;

  }
}
</style>
