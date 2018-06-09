<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>

    <member-list :members="members">
    </member-list>
  </div>
</template>

<script>
import MemberList from './components/MemberList.vue';
import Member from './components/Member.vue';
export default {
  name: 'app',
  components: { MemberList, Member },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      members: 
      [
        {
          first_name: 'Franco Gabriel',
          last_name: 'Ledesma',
          age: 20,
        },
        {
          first_name: 'Nelson',
          last_name: 'Campos',
          age: 20,
        },
        {
          first_name: 'Cecilia',
          last_name: 'Regatuso',
          age: 20,
        },
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
