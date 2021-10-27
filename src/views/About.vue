<template>
  <div class="about">
  <div class="containerabout">
  <h3> About Us </h3>
  <p> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur lorem ipsum dolor. </p>
  </div>
  </div>
</template>

<script>


export default {
  name: "About",
};
</script>

<style>
.about {
  background-image: url(../assets/B.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  padding-top: 10px;
  padding-bottom:200px ;
}

.containerabout {
  max-width: 1100px;
  position: center;
  top: 10px;
  margin: auto;
  overflow: auto;
  min-height: 400px;
  border: 1px solid white;
  padding: 30px;
  border-radius: 5px;
  background-color: white;
}

</style>

