<template>
  <div>
    <ol>
      <todo-item
        v-for="item in list"
        v-bind:nihao="item"
        v-bind:key="item.id"
      ></todo-item>
    </ol>
  </div>
</template>

<script>
import Vue from 'vue'
Vue.component('todo-item', {
  props: ['nihao'],
  template: '<li>{{nihao.text}}</li>'
})

export default {
  name: 'Big1-7',
  data () {
    return {
      list: [
        {id: 0, text: 'apple'},
        {id: 1, text: 'banana'},
        {id: 2, text: 'juice'}
      ]
    }
  }
}
</script>

<style scoped>

</style>
