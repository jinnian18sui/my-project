<template id="app-4">
    <div>
      <ol>
        <li
          v-for="todo in todos"
        >
          {{todo.text}}
        </li>
      </ol>
    </div>
</template>

<script>
export default {
  name: 'Big1-4',
  data () {
    return {
      todos: [
        {text: '学习JavaScript'},
        {text: '学习Vue'},
        {text: '学习amap'}
      ]
    }
  }
}
</script>

<style scoped>

</style>
