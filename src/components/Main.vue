<template>
  <div class="content">
    <div class="category about"><router-link to="/about">关于我们</router-link></div>
    <div class="category event"><router-link to="/event">未来活动</router-link></div>
    <div class="category history"><router-link to="/history">往期活动</router-link></div>
    <div class="category members"><router-link to="/members">社团成员</router-link></div>
    <div class="category contact"><router-link to="/contact">加入我们</router-link></div>
  </div>
</template>

<script>
  export default {
  }
</script>

<style scoped>
  .content {
    background-color: #333333;
    height: 60%;
    width: 70%;
    margin: 0 auto;
    border-radius: 1em;
    box-shadow: 0.5em 0.4em 3em gray;
    margin-top: 1em;
    position: relative;
    top: -3%;
    display: -webkit-flex; /* Safari */
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: flex-start;
  }
  .category {
    float: left;
    color: #333333;
    font-size: 2em;
    flex: 1.0;
    writing-mode: vertical-lr;
    letter-spacing: 1em;
    text-align: center;
    text-indent: 1em;
    vertical-align:middle;
    padding-left: 2em;
    font-family: pingfang, "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", "微软雅黑", Arial,sans-serif;
  }
  .category:hover > a {
    color: white;
  }
  .about {
    background-color: #f7f7f7;
    border-radius: 0.4em 0 0 0.4em;
    transition: 0.7s;
  }
  .about:hover {
    background-color: #333333;
    color: #f7f7f7;
  }
  .event {
    background-color: #f3f3f3;
    transition: 0.7s;
  }
  .event:hover {
    background-color: #333333;
    color: #f3f3f3;
  }
  .history {
    background-color: #efefef;
    transition: 0.7s;
  }
  .history:hover {
    background-color: #333333;
    color: #efefef;
  }
  .members {
    background-color: #ebebeb;
    transition: 0.7s;
  }
  .members:hover {
    background-color: #333333;
    color: #ebebeb;
  }
  .contact {
    background-color: #e7e7e7;
    border-radius: 0 0.4em 0.4em 0;
    transition: 0.7s;
  }
  .contact:hover {
    background-color: #333333;
    color: #e7e7e7;
  }
  a {
    text-decoration: none;
    color: #333333;
  }
</style>
