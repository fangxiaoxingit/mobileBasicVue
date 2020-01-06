<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="index">Hello World! </div>
    <div class="index_2">Hello World! </div>
    <i class="iconfont icon-shuju1"></i> <br>
    <button class="btn">按钮</button> <br>
    <p class="text-theme-color">主题色</p>
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
  mounted:function(){

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.iconfont{
  color: @theme-color;
  font-size: 30px;
}
.index{
  width: 750px;
  font-size: 30px;
  line-height: 3;
}
.index_2{
  font-size: 30px;
  line-height: 3;
}
.text-theme-color{
  color: @theme-color;
}
.btn{
  border: none;
  color: #fff;
  padding: 10px 20px;
  background-color: @theme-color;
}
h1{
  font-size: 50px;
  line-height: 2;
}
</style>
