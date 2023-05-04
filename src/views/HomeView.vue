<template>
  <div class="home">
    <h1>人坤</h1>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  data () {
    return {
      info: '人坤'

    }
  },
  components: {
    HelloWorld
  }
}
</script>
5
