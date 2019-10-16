<template>
  <div class="mainhome">
    <!-- 顶部栏 -->
    <div class="hometop">
      <!-- 左边 -->
      <div class="leftte">
        <span>深圳</span>
        <van-icon color="white" name="arrow-down" />
      </div>
      <!-- 右边 -->
      <div class="secondcol">
        <div class="inputserch">
          <!-- <input type="text" placeholder="输入关键词" /> -->
          <van-icon color="orange" name="search" />
        </div>
        <div>
          <van-icon color="white" name="location" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
  created() {},
  methods: {}
}
</script>

<style lang='less' scoped>
.mainhome {
  position: relative;
  width: 100%;
  height: 100%;
  .hometop {
    position: fixed;
    top: 0;
    z-index: 100;
    background-color: #ff7900;
    width: 375px;
    height: 80px;
    line-height: 80px;
    .leftte {
      position: absolute;
      left: 20px;
      top: 50%;
      transform: translateY(-50%);
      span {
        margin-right: 10px;
        color: #fff;
      }
    }
    .secondcol {
      position: absolute;
      right: 20px;
      top: 50%;
      transform: translateY(-50%);
      display: flex;
      justify-content: space-between;
      align-items: center;
      height: 40;
      .inputserch {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: #fff;
        width: 100%;
        height: 20px;
        border-radius: 5px;
        margin-right: 10px;
        padding: 0 10px;
      }
    }
  }
  // .hometop {
  //   position: fixed;
  //   top: 0;
  //   z-index: 100;
  //   background-color: #ff7900;
  //   width: 375px;
  //   height: 80px;
  //   line-height: 80px;
  //   .leftte {
  //     position: absolute;
  //     left: 20px;
  //     top: 50%;
  //     transform: translateY(-50%);
  //     text {
  //       margin-right: 10px;
  //       color: #fff;
  //     }
  //   }
  //   .secondcol {
  //     position: absolute;
  //     right: 20px;
  //     top: 50%;
  //     transform: translateY(-50%);
  //     display: flex;
  //     justify-content: space-between;
  //     align-items: center;
  //     height: 100%;
  //     .inputserch {
  //       display: flex;
  //       justify-content: space-between;
  //       align-items: center;
  //       background-color: #fff;
  //       width: 500px;
  //       height: 50px;
  //       border-radius: 25px;
  //       margin-right: 20px;
  //       padding: 0 10px;
  //     }
  //   }
  // }
}
</style>
