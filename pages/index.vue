<template>
  <v-app dark class="ml-12 mt=12">
    <AddTodo/>
    <v-spacer></v-spacer>
    <todolist/>
  </v-app>
</template>

<script>
import todolist from './todolist'
import AddTodo from '@/components/AddTodo'

export default {
  data() {
    return {};
  },
  components:{
    todolist,
    AddTodo,
  }
};
</script>


<style>

</style>