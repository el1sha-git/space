<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
*{
  padding: 0;
  margin: 0;
}
.container{
  width: 60%;
}
@media screen and (max-width: 480px) {
  .container{
    width: 90%;
  }
}
@media screen and (max-width: 900px) and (min-width: 480px) {
  .container{
    width: 70%;
  }
}
.p_cont{
  width: 100%;
  display: flex;
  justify-content: center;
}
</style>
