<template>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark" id="navbarsettings">
  <a class="navbar-brand" > Lorem Ipsum </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <router-link class="nav-link" to="/">Home</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/about">About Us</router-link>
      </li>
    </ul>
  </div>
</nav>

<router-view />

<footer class="footer bg-dark">
  <div class="container">
  <div class="columns">
    <div class="column">
      <p id="textprop"> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur lorem ipsum dolor. </p>
    </div>
    <div class="column2">
      
      <a class="icon"> <fa :icon="['fab', 'facebook']" /></a>
      <a class="icon"> <fa :icon="['fab', 'twitter']" /></a>
      <a class="icon"> <fa :icon="['fab', 'instagram']" /></a>
      <a class="icon"> <fa :icon="['fab', 'linkedin']" /></a>
      <a class="icon"> <fa :icon="['fab', 'github']" /></a>
    </div>
  </div>
  </div>

</footer>
</template>


<script>
export default {
  name: "App",
};
</script>


<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.navbar-brand {
  padding-left: 30px;
  font-weight: bold;
}

.column2 {
  padding-bottom: 15px;
}

.icon {
  padding-left: 20px;
  padding-right: 20px;
  color: white;
}

#nav {
  padding: 30px;
}

#navbarsettings {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
}

#textprop {
  padding-top: 10px;
  color: white;
}



</style>
