<template>
  <div id="app">
    <div id="header-container">
      <div>Logo</div>
      <div>powered by</div>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  height: 120px;
  background-color: #444444;
  color: #ffffff;
}
</style>
