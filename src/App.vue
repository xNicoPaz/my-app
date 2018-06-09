<template>
  <div id="app">
    <message>
      <span slot="title">Esto es</span>
      <span slot="body">SPARTA</span>
    </message>
  </div>
</template>

<script>
import Message from './components/Message.vue';

export default {
  name: 'app',
  components: { Message },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App, Nico'
    }
  }
}
</script>
