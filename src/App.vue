<template>
  <body>
    <div class="container">
      <div class="navbar">
        <img src="images/logo.png" class="logo">
        <nav>
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Styles</a></li>
            <li><a href="#">About</a></li>
          </ul>
        </nav>
        <img src="images/menu.png" class="menue-icon">
      </div>
    </div>
  </body>
</template>

<script>

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
.container{
  width: 100%;
  height: 100vh;
  background-image: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)), url('https://image.freepik.com/free-vector/beauty-care-seamless-pattern_93150-741.jpg');
  background-position: center;
  background-size: cover;
}
</style>
