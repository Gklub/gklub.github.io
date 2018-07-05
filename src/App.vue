<template>
  <div id="app">
    <div class="container">
      <div class="title">GeeKlub</div>
      <div class="slogan">Talk is cheap, show me the code.</div>
      <router-view></router-view>
    </div>
    <el-row class="footer">
      <el-col :span="6" :offset="9">
        <p>
          Made by  ❤  <a href="https://fogdong.github.io/">FogDong</a>
        </p>
      </el-col>
    </el-row>
  </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>

<style>
  @font-face {
    font-family: pingfang;
    src: url("./assets/pingfang.ttf");
  }
  html {
    height: 100%;
    width: 100%;
    margin: 0;
    padding: 0;
  }
  body {
    margin: 0;
    font-family: "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "微软雅黑", Arial,sans-serif;
    width: 100%;
    height: 100%;
    background-image: url("./assets/todobg.jpg");
    position: absolute;
    background-size: 100%;
    padding: 0;
  }
  #app {
    height: 100%;
  }
  .container {
    height: 100%;
    padding: 0;
  }
  .title {
    color: #333333;
    font-family: pingfang, "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "微软雅黑", Arial, sans-serif;
    font-size: 8em;
    text-align: center;
    letter-spacing: 0.05em;
  }
  .slogan {
    color: white;
    font-family: pingfang, "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "微软雅黑", Arial,sans-serif;
    text-align: center;
    background-color: #333333;
    font-size: 1.2em;
    margin: 0 auto;
    width: 50%;
    letter-spacing: 0.5em;
    padding: 0 2em;
    border-radius: 0.3em;
    position: relative;
    top: -5%;
  }
  .footer {
    background: linear-gradient(to bottom, rgba(0,0,0,0.2) 0%, rgba(0,0,0,0.3) 100%);
    text-align: center;
    color: #888;
    padding: 10px;
  }
  a {
    text-decoration: none;
    color: #888;
  }
  @media only screen and (max-width: 1000px) {
    body {
      background-position-x: 50%;
    }
  }
</style>

