<template>
  <div class="hello">
    <div class="center">
      <p>M:{{ msg }}</p> 
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped src="../assets/css/style.css">
</style>
