<template>
  <div class="home">
    <Menu/>
    <Intro/>
  </div>
</template>

<script>
// @ is an alias to /src
import Menu from '../components/Menu.vue'
import Intro from '../views/Intro.vue'

export default {
  name: 'Home',
  components: {
    Menu,
    Intro
  }
}
</script>
