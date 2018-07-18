<template>
    <div>
      <p>{{message}}</p>
      <p>{{tellMe}}</p>
      <input v-model="message"/>
      <br>
      <br>
      <br>
      <input v-model="tellMe"/>
    </div>
</template>

<script>
export default {
  name: 'Big1-6',
  data () {
    return {
      message: 'Hello Vue!!!',
      tellMe: 'sjfalsjdo'
    }
  }
}
</script>

<style scoped>

</style>
