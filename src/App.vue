<template>
  <div id="app" class="container">
    <img src="https://cdn.onlinewebfonts.com/svg/img_106582.png" class="logo">
  <todo-list></todo-list> 
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld' 
import TodoList from './components/Todolist'


export default {
  name: 'App',
  components: {
    HelloWorld,
    TodoList,
  }
}
</script>

<style> 

* {
  box-sizing: border-box; 
  color: red;
}

.container {
  max-width: 600px; 
  margin: 0 auto;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} 

.logo{
  display: block;
  margin: 20px auto;
  height: 75px;
} 

</style>
