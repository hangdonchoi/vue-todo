<template>
  <div>
    <Todo-Header></Todo-Header>
    <Todo-Input></Todo-Input>
    <Todo-List></Todo-List>
    <Todo-Footer></Todo-Footer>
  </div>
</template>

<script>
import TodoHeader from '../components/TodoHeader.vue'
import TodoFooter from '../components/TodoFooter.vue'
import TodoInput from '../components/TodoInput.vue'
import TodoList from '../components/TodoList.vue'

export default {
  components:{
    'Todo-Header':TodoHeader,
    'Todo-Footer':TodoFooter,
    'Todo-Input':TodoInput,
    'Todo-List':TodoList,

  }
}
</script>

<style>
h1 {
    color: #2F3B52;
    font-weight:900;
    margin: 2.5rem 0 1.5rem
}

body {
    color: #F6F6F6;
  text-align: center;
  background-color: #F6F6F6;
}
input {
  border-style: groove;
  width: 200px;

}
button {
  border-style: groove;
}
.shadow {
  box-shadow: 5px 10px 10px rgba(0, 0, 0, 0.03)
}
</style>
