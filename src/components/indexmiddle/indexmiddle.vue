<template>
  <div class="index-m-content">
    <el-row class="middletop">
      <el-row class="huodonglist">
        <el-col :span="1" class="huodonglistl">
          <i class="iconfont icon-fanhui"></i>
        </el-col>
        <el-col :span="22"  class="huodonglistm">
          <el-col :span="4"><div class="huodonglistml">全部</div></el-col>
          <el-col :span="4"><div class="huodonglistml">奶茶</div></el-col>
          <el-col :span="4"><div class="huodonglistml">水果茶</div></el-col>
          <el-col :span="4"><div class="huodonglistml">咖啡</div></el-col>
          <el-col :span="4"><div class="huodonglistml">甜品</div></el-col>
          <el-col :span="4"><div class="huodonglistml">小吃</div></el-col>
        </el-col>
        <el-col :span="1" class="huodonglistl rotate180">
          <i class="iconfont icon-fanhui"></i>
        </el-col>
      </el-row>
    </el-row>
    <el-row class="middlebody" :gutter="10">
      <el-col :span="6"><div  class="grid-content">好喝的拿铁咖啡</div></el-col>
      <el-col :span="6"><div  class="grid-content">好喝的拿铁咖啡</div></el-col>
      <el-col :span="6"><div  class="grid-content">好喝的拿铁咖啡</div></el-col>
      <el-col :span="6"><div  class="grid-content">好喝的拿铁咖啡</div></el-col>
      <el-col :span="6"><div  class="grid-content">好喝的拿铁咖啡</div></el-col>
      <el-col :span="6"><div  class="grid-content">好喝的拿铁咖啡</div></el-col>
      <el-col :span="6"><div  class="grid-content">好喝的拿铁咖啡</div></el-col>
      <el-col :span="6"><div  class="grid-content">好喝的拿铁咖啡</div></el-col>
    </el-row>
    <el-row></el-row>
  </div>
</template>

<script>
export default {
  name: 'indexmiddle'
}
</script>

<style scoped>
  .middletop{
    padding: 0.5rem 0.5rem;
    border-bottom:  1px solid rgb(246,246,246);
  }
  .middletop .el-col{
    line-height: 2.6rem;
    text-align: center;
    font-size: 0.8rem;
  }
  .huodonglistl{
    background-color: rgb(238,241,246);
    border-radius: 0.2rem 0 0 0.2rem;
  }
  .huodonglistm{
    padding-left: 0.5rem
  }
  .huodonglistm .el-col{
    padding-right: 0.5rem
  }
  .huodonglistml{
    border: 1px solid rgb(216,220,229);
    height: 96%;
    border-radius: 0.2rem;
  }
  .middlebody{
    height: 35rem;
    padding: 0.5rem 0.5rem;
  }
  .middlebody>.el-col{
    margin-top: 0.5rem;
  }
  .middlebody .grid-content{
    height: 5.5rem;
    background-color:  rgb(255,235,235);
    text-align: center;
    padding-top: 1rem;
  }
</style>
