<template>
  <div class="main">
      <header class="head"></header>
        <div class="left"></div>
        <div class="right"></div>
      <footer class="footer">
          CopyRight By 肖景天
      </footer>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg:'Hello world'
    }
  }
}  
</script>

<style>
.main{
  margin:0px;
  min-height: 700px;
}
.head{
  position: absolute;
  width:100%;
  top:0px;
  height:40px;
  background-color:#00abff;
}
.left{
  position: absolute;
  width:200px;
  top:40px;
  bottom:40px;
  background-color: #eee;
}
.right{
  position: absolute;
  width:100%;
  left:200px;
  top:40px;
  bottom:40px;
  background-color: #fff;
}
.footer{
  position: absolute;
  width:100%;
  bottom:0px;
  height:40px;
  line-height: 40px;
  background-color:#e5ff00;
  text-align: center
}

</style>
