<template>
  <v-app id="app">
    <router-view />
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>

<style>
* {
  font-family: "Poppins";
}

#app {
  min-height: 100vh;
  height: 100%;

  background: linear-gradient(359.27deg, #070631 3.1%, #1672b4 99.39%);
}
</style>
