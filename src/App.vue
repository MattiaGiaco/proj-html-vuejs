<template>
  <div id="app">
    <Header :menuList='menuList' />
    <Main />
    <Footer :posts='posts' />
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
  },
  data() {
    return {
      menuList: [
        {
          url: '/home',
          text: 'Home',
          current: true
        },
        {
          url: '/Services',
          text: 'Services',
          current: false
        },
        {
          url: '/About',
          text: 'About',
          current: false
        },
        {
          url: '/Videos',
          text: 'Videos',
          current: false
        },
        {
          url: '/Blog',
          text: 'Blog',
          current: false
        },
        {
          url: '/Store',
          text: 'Store',
          current: false
        },
      ],
      posts: [
        'The best protein shake',
        'Ultimate cardio workout',
        'New juices available now',
        'Tips to find training partners',
        '20 best healthy recipes'
      ]
    }
  }
}
</script>

<style lang="scss">

  @import './assets/style/generals.scss';


</style>
