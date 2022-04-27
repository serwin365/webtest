<template>
  <div class="hd">
    <ul>
      <li><a href="#">海军力量</a></li>
      <li><a href="#">空军力量</a></li>
      <li><a href="#">台湾信息</a></li>
      <li><a href="#">香港问题</a></li>
      <li><a href="#">一国两制</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: '',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
  ul{
    list-style-type: none;
    margin:0;
    padding:0;
    background-color:#333;
    position: fixed;
    top:0;
    width:100%;
  }
  li{
    float:left;
    width:20%;
  }
  li a{
    display: block;
    color:white;
    text-align: center;
    text-decoration: none;
    padding: 20px 0;
    font-size: 18px;
  }
  li a:hover:not(.active) {
    background-color: #111;
}
</style>
