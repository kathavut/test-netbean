<template>
    <div>
        <router-view></router-view>
    </div>
</template>

<script>
    import Header from './components/Header.vue'
    import Footer from './components/Footer.vue'
    import Login from './components/Login.vue'
export default {
    name: 'app',
    components:{
        'com-header':Header,
        'com-footer':Footer,
        'cs-login':Login
    },
  data () {
    return {
      title: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>
    
</style>
