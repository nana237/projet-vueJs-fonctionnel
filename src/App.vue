<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
  @font-face{
    font-family:Korean ;
    src: url("assets/Korean_Calligraphy.ttf");
    font-weight: normal;
  }

   @font-face{
    font-family:Korean ;
    src: url("assets/Korean_Calligraphy.ttf");
    font-weight: bold;
  }

   @font-face{
    font-family:Korean ;
    src: url("assets/Korean_Calligraphy.ttf");
    font-weight: 100;
  }


#app {
  font-family: Korean, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


</style>
