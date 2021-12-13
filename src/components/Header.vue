<template>
  <header>

    <div class="container d-flex justify-content-between align-items-center h-100">

      <div class="mg_logo">
        <img src="../assets/img/logo.png" alt="Logo">
      </div>

      <div class="mg_menu d-flex align-items-center">
        <ul class="d-flex">
          <li><a href="#">Home</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Store</a></li>
        </ul>

        <button class="mg_btn">Schedule a workout</button>

        <a href="#"><i class="fas fa-shopping-cart"></i></a>
        <a href="#"><i class="fas fa-search"></i></a>
      </div>

    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style lang="scss" scoped>
  header{
    height: 100px;
    background-color: #060606;
    .mg_menu{
      
      li a{
        text-decoration: none;
        color: #78787a;
      }
    }
    button{
      background-color: #4154fe;
    }
  }
</style>