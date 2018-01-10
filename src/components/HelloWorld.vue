<template>
  <div class="hello">
    外部页面
    <p></p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  mounted () {
    alert(1)
    alert(myCallback)
    ref.close();
    console.log(myCallback)
  }
}
</script>

<style scoped>
.hello{
  font-size: .373333rem;
  color: #dddddd;
}
</style>
