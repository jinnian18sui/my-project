<template>
  <div>
    <p>{{message}}</p>
    <button v-on:click="reverseMessage">逆转消息</button>
  </div>
</template>

<script>
export default {
  name: 'Big1-5',
  data () {
    return {
      message: 'Hello Vue.js'
    }
  },
  methods: {
    reverseMessage: function () {
      this.message = this.message.split('')
      alert(this.message)
      this.message = this.message.reverse()
      alert(this.message)
      this.message = this.message.join('V')
      alert(this.message)
    }
  }
}
</script>

<style scoped>

</style>
