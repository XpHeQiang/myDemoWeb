<template>
  <div class="hello">
    外部页面
    <p></p>
    <button @click="avb"></button>
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
  },
  methods: {
    avb(){
      window.location.href = "http://www.baidu.com";
    }
  }
}
</script>

<style scoped>
.hello{
  font-size: .373333rem;
  color: #dddddd;
}
</style>
