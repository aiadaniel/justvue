<template>
    <div id="app">
        <input v-model="newTodo" v-on:keyup.enter="addTodo">
        <ul>
            <li v-for="todo in todos">
                <span>{{ todo.text }}</span>
                
                <button v-on:click="removeTodo($index)">X</button>
            </li>
        </ul>
    </div>
</template>


<script>
export default {
  data () {
    return {
      todos: [xx,yy]
    }
  }
}
</script>