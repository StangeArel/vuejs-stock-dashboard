<template>
  <MyCard>
    <h1>Überschrift</h1>
    <p>Dies ist ein Beispiel</p>
  </MyCard>
</template>

<script>
import MyCard from "./components/MyCard";

export default {
  name: 'App',
  components: { MyCard }
}
</script>


<style>
body {
  margin: 0;
}

#app {
  min-height: 100vw;
  width: 100vh;
  padding: 100px;
  background: radial-gradient(71.11% 100% at 50% 0%, #020204 14.6%, #011F35 100%);
  box-sizing: border-box;
}
</style>
