<template>
  <div id="app-3">
    <p v-if="seen">你可以看见我了</p>
  </div>
</template>

<script>
export default {
  name: 'Big1-3',
  data () {
    return {
      seen: true
    }
  }
}
</script>

<style scoped>

</style>
