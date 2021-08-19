<template>
  <div class="demo">
    <h2>学习名称:{{name}}</h2>
    <h2>学习地址:{{address}}</h2>
    <button @click="showName">点我提示学校名</button>
  </div >
</template>
<script>
// 默认暴露 export default 暴露内容
export default{
  name:'School',
  data(){
    return{
      name:'尚硅谷',
      address:'北京'
    }
  },
  methods:{
    showName(){
      alert(this.name)
    }
  }
}
</script>
<style>
.demo{
  background:red;
}
</style>
