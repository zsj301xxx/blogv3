<template>
  <div class="mainbox">
    <el-row
      type='flex'
      justify="center"
      style="height:100%"
    >
      <el-col :span="16">
        <div class="nav">
          <span class="fontstyle">
            墨鱼个人博客 |
            <span style="font-size:16px">
              排名技术建站
            </span>
          </span>
          <el-space wrap>
            <el-link :underline="false">无下划线</el-link>
            <el-link :underline="false">无下划线</el-link>
            <el-link :underline="false">无下划线</el-link>
            <el-link :underline="false">无下划线</el-link>
            <el-link :underline="false">无下划线</el-link>
            <el-link :underline="false">无下划线</el-link>
          </el-space>
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  name:"Header"
}
</script>

<style lang="scss" scoped>
.mainbox {
  width: 100%;
  height: 70px;
  background: #000;
  .nav {
    height: 100%;
    background: transparent;
    display: flex;
    justify-content: flex-start;
    align-items: center;
  }
  .fontstyle {
    font-family: 'Microsoft YaHei';
    color: white;
    font-size: 22px;
    cursor: default;
  }
}
.mainbox::before {
  background: #000
    linear-gradient(
      to left,
      #4cd964,
      #5ac8fa,
      #007aff,
      #34aadc,
      #5856d6,
      #ff2d55
    );
  content: '';
  height: 5px;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
}
</style>
