<template lang="pug">
  #app
    Top
    #content
      #left
        Menu
        Update
      #right
        Mar
        Main
    Footer
</template>

<script>
import Top from './components/Top.vue'
import Menu from './components/Menu.vue'
import Update from './components/Update.vue'
import Mar from './components/Mar.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Top,
    Menu,
    Update,
    Mar,
    Main,
    Footer
  }
}
</script>
