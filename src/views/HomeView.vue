<template>
  <v-app id="home">
    <NavBar />
    <v-container fluid>
      <div class="head"></div>
    </v-container>
  </v-app>
</template>

<script setup>
// Components
import NavBar from "@/components/NavBar.vue";
</script>

<style scoped>
.v-container {
  padding: 16px 0;
}
.head {
  position: relative;
  text-align: center;
  padding: 12px;
  margin-bottom: 6px;
  height: 400px;
  width: 100%;
  color: white;
}
.head:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 50%;
  background: black;
}
</style>
