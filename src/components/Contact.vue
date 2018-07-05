<template>
  <div class="content">
    <div class="left">Contact</div>
    <div class="right">
      Contact
    </div>
  </div>
</template>

<script>
  export default {
  }
</script>

<style scoped>
  .content {
    background-color: #f7f7f7;
    height: 60%;
    width: 70%;
    margin: 0 auto;
    border-radius: 1em;
    box-shadow: 0.5em 0.4em 3em gray;
    margin-top: 1em;
  }
  .left {
    background-color: #333333;
    width: 15%;
    height: 100%;
    border-radius: 0.2em 0 0 0.2em;
    font-size: 4em;
    letter-spacing: 0.1em;
    text-indent: 0.5em;
    writing-mode: vertical-lr;
    color: #f7f7f7;
    font-family: pingfang;
    float: left;
  }
  .right {
    font-family: pingfang;
    font-size: 1.5em;
    color: #333333;
    padding-top: 0.5em;
    width: 80%;
    float: right;
    padding-left: 0.5em;
  }
</style>
