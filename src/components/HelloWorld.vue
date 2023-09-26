<template>
  <div class="hello">
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      message: 'Hello, Vue!'
    }
  }
}
</script>

<style scoped>
.hello {
  text-align: center;
  margin-top: 40px;
}
</style>