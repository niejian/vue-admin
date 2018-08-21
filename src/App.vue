<template>
  <div>
     <Header/>
     <Menu/>
     <Main/>
  </div>
</template>

<script>
//Menu-- 左侧菜单栏
import Menu from './components/main/Menu.vue'
import Header from './components/main/Header.vue'
import Main from './components/main/Main.vue'




export default {
  name: 'App',
  //注册主键
  components: {
        Menu,
        Header,
        Main
  }
}
</script>

<style>
</style>
