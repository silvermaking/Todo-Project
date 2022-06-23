<template>
  <div>
    <todo-list-item-vue v-for="todo in todos" :key="todo.date" :todo="todo"></todo-list-item-vue>
  </div>
</template>

<script>
import TodoListItemVue from "./TodoListItem.vue";

export default {
  name: "TodoList",
  components: {
    TodoListItemVue
  },
  computed: {
    todos: function() {
      return this.$store.state.todos;
    }
  }
};
</script>

<style>
</style>