<template>
  <div class="about container">
    <h1 class="page-header">利用vue-webpack,脚手架创建的案例，设计json:server，本地服务器获取数据</h1>
    <p>vue init webpack 项目名称(不能有大写) ---安装vue-cli脚手架</p>
    <p>cd 项目文件夹 》》》npm run dev</p>
    <p>cnpm install --- 创建 node_modules</p>
    <p>cnpm install vue-router --save(根据需求安装路由)</p>

    <br/>
    
    <p>json-server存储本地数据(视频:https://www.bilibili.com/video/av51530091/?p=1)</p>
    <p>postman用法了解，如何传到网上</p>
    <p>获取数据时要将本地的json打开</p>
    
  </div>
</template>

<script>
export default {
  name: 'about',
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
p{
  font-size: 18px;
  font-weight: bold;
}
</style>
