<template>
  <div id="app">
    <h1>Todo List</h1>
    <todo-list-vue></todo-list-vue>
    <todo-form-vue></todo-form-vue>
  </div>
</template>

<script>
import TodoListVue from './components/TodoList.vue'
import TodoFormVue from './components/TodoForm.vue'

export default {
  name: 'App',
  components: {
    TodoListVue,
    TodoFormVue,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
