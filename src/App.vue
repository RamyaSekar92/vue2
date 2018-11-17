<template>
  <div id="app">
    <header>
      <nav class="navbar navbar-expand-lg navbar-dark default-color-dark fixed-top">
        <a class="navbar-brand" href="index.html" style="color: #333;"><img src="https://vuejs.org/images/logo.png" style="width: 35px;"/>VUE JS</a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse " id="navbarSupportedContent">
          
          <ul class="navbar-nav ml-auto nav-flex-icons">
             <li class="nav-item"><a class="nav-link" href="#">Menu 1</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Menu 2</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Menu 3</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Menu 4</a></li>
          </ul>
        </div>
      </nav>
    </header>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
