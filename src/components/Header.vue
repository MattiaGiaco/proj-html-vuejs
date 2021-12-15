<template>
  <header>

    <div class="container d-flex justify-content-between align-items-center h-100">

      <div class="mg_logo">
        <img src="../assets/img/logo.png" alt="Logo">
      </div>

      <div class="mg_menu d-flex align-items-center">
        <ul class="d-flex">
          <li
            v-for="(item, index) in menuList"
            :key="index"
          >
            <a :href="item.url" :class="{active: item.current}">{{item.text}}</a>
          </li>
        </ul>

        <button class="mg_btn">Schedule a workout</button>

        <a href="#"><i class="fas fa-shopping-cart mx-4"></i></a>
        <a href="#"><i class="fas fa-search"></i></a>
      </div>

    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
    menuList: Object
  }
}
</script>

<style lang="scss" scoped>
  header{
    height: 100px;
    background-color: #060606;
    .mg_menu{
      li{
        margin: 0 10px;
      }
      li a{
        text-decoration: none;
        color: #78787a;
        font-weight: 600;
        &.active,
        &:hover{
          color: white;
        }
      }
    }
    a{
      color: #78787a;
      &:hover{
        color: white;
      }
    }
  }
</style>