<template>
  <div id="app">
    <div id="header-container">
      <div id="logo-container">
        <img src="@/assets/logos/logo.png" />
      </div>
      <div id="powered-by-container">
        <div>
          <span>powered by</span>
          <img src="@/assets/logos/r00tstici.png" />
        </div>
      </div>
    </div>
    <div id="search-bar-conrainer">
      <v-text-field
        hide-details
        outlined
        placeholder="Search"
        dark
        append-icon="search"
        dense
      >
      </v-text-field>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #e7e7e7;
  min-height: 100vh;
}

#header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 20px 20px;
  background-color: #232323;
  color: #ffffff;
}

#header-container #logo-container > img {
  padding: 20px 0;
  height: 100px;
}

#header-container #powered-by-container {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: flex-end;
}

#header-container #powered-by-container > div {
  display: flex;
  align-items: center;
}

#header-container #powered-by-container span {
  margin-right: 12px;
}

#header-container #powered-by-container img {
  height: 42px;
  border-radius: 4px;
}

#search-bar-conrainer {
  background-color: #393939;
  padding: 16px;
}
</style>
