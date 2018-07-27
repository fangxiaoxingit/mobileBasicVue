<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="index">Hello World! </div>
    <div class="index_2">Hello World! </div>
    <i class="iconfont icon-shuju1"></i> <br>
    <button class="btn">按钮</button> <br>
    <button class="btn btn-50">按钮50</button>
    <button class="btn btn-100">按钮100</button>
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
@import "../assets/less/index.less";
.iconfont{
  color: #42b983;
  font-size: 30px;
}
.index{
  width: 750px;
  font-size: 30px;
  background: @color-background;
  color: @color-theme;
  line-height: 3;
}
.index_2{
  font-size: 30px;
  line-height: 3;
}
h1{
  font-size: 50px;
  line-height: 2;
}
</style>
