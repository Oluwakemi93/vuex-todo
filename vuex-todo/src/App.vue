<template>
  <div id="app">
    <div class="container">
      <AddTodo/>
      <FilterTodos/>
      <Todos/>
    </div>
  </div>
</template>

<script>
import Todos from './components/Todos.vue';
import AddTodo from './components/AddTodo.vue';
import FilterTodos from './components/FilterTodos.vue';

export default {
  name: 'app',
  components: {
    Todos,
    AddTodo,
    FilterTodos
  }
};
</script>

<style>
body {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  line-height: 1.6;
  background: #eBf7f0;
  margin-left: 110px;
}
.container {
  max-width: 1100px;
  margin: au   to;
  overflow: auto;
  padding: 0zren;
}
</style>
