<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div id="app">
    <Quiz />
  </div>
</template>

<script>
import Quiz from './components/Quiz.vue'

export default {
  name: 'App',
  components: {
    Quiz
  }
}
</script>

<style>

body{
  background-color: #d9f1d0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  color: black;
 }


 #app h1 {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  color: green;
  font-size: 4.5em;
  margin-bottom: 20px;
}

h2 {
  font-size: 2em;
  margin-bottom: 15px;
}

h3 {
  font-size: 1.8em;
  margin-bottom: 10px;
}

#app p {
  font-size: 1.1em;
  line-height: 1.8;
  margin-bottom: 25px;
}

a {
  color: white;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

#app .button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #007bff;
  color: white;
  border-radius: 5px;
  font-size: 1.1em;
  text-transform: uppercase;
  transition: background-color 0.3s ease;
}

#app .button:hover {
  background-color: #0056b3;
}


.section {
  padding: 40px 0;
}


</style>