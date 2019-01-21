<template>
  <div class="information">

    <el-col :span="6" class="left"  >
      <el-card class="top box">

      </el-card>
      <el-card class="center box">

      </el-card>
      <el-card class="bottom box">

      </el-card>
    </el-col>
    <el-col :span="11" class="center" >
      <el-card class="top box">

      </el-card>
      <el-card class="bottom box">

      </el-card>
    </el-col>
    <el-col :span="6" class="right">
      <el-card class="top box">

      </el-card>
      <el-card class="center box">

      </el-card>
      <el-card class="right box">

      </el-card>
    </el-col>
  </div>

</template>

<script>
  export default {
    data() {

    },
    methods: {}
  }
</script>

<style lang="scss">
  .information {
    padding: 0px;
    background-color: transparent;

    /*.box {
      box-shadow: 0 0 1rem 0.01rem rgba(0, 0, 0, 0.3);
    }*/

    .left {
      margin-right: 15px;
      margin-left: 15px;

      .top {
        width: 100%;
        height: calc(35vh);
      }
      .center {
        width: 100%;
        height: calc(27vh);
        margin-top: 10px;
        margin-bottom: 10px;
      }
      .bottom {
        width: 100%;
        height: calc(27vh);
      }
    }
    .center {
      margin-right: 15px;
      .top {
        width: 100%;
        height: calc(57vh);
      }
      .bottom {
        width: 100%;
        height: calc(33vh);
        margin-top: 10px;
      }
    }
    .right {
      .top {
        width: 100%;
        height: calc(35vh);
      }
      .center {
        width: 100%;
        height: calc(27vh);
        margin-top: 10px;
        margin-bottom: 10px;
      }
      .right {
        width: 100%;
        height: calc(27vh);
      }
    }
  }


</style>

