<template>
  <div class="home">
    
    <div class="containermk2"> 

      <h1 class="textedit"> Lorem ipsum </h1>
    </div>
    
  </div>
</template>

<script>


export default {
  name: "Home",
};
</script>

<style>
.home {
  background-image: url(../assets/A.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  padding-top: 50px;
  padding-bottom: 50px;
 
}

.containermk2 {
  max-width: 500px;
  position: center;
  top: 10px;
  margin: auto;
  overflow: auto;
  min-height: 350px;
  border: 1px solid white;
  padding: 30px;
  border-radius: 7px;
  background-color: white;
}
.textedit {
  position: center;
  padding: 100px;
}

</style>
