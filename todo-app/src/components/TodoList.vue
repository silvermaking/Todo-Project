<template>
  <div>
	<todo-list-item-vue></todo-list-item-vue>
  </div>
</template>

<script>
import TodoListItemVue from './TodoListItem.vue'

export default {
	name: 'TodoList',
	components: {
		TodoListItemVue,
	}
}
</script>

<style>

</style>