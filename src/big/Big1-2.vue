<template>
  <div id="app-2">
    <span v-bind:title="message">
      v-bind:title 鼠标停留几秒钟
    </span>
  </div>
</template>

<script>
export default {
  name: 'Big1-2',
  data () {
    return {
      message: 'tell where i can stand'
    }
  }
}
</script>

<style scoped>

</style>
