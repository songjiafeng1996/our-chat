<template>
  <div id="app">
    <div class="top-gap"></div>
    <div class="top-nav">
      <div class="left-login-icon flex-h-center fl">
        <img src="./assets/images/logo (1).png" alt="">
      </div>
      <div class="right-nav-list fr">
        <div class="more-icon flex-h-center fr">
          <div class="sina-out flexCenter">
            <img src="./assets/images/sina.png" alt="">
          </div>
          <div class="search-out flexCenter fr" @click="getSearch()">
            <img src="./assets/images/search_icon_header.png" alt="">
          </div>
        </div>
        <div class="nav-list fr">
          <span>FIX作品</span>
          <span>盘度失效修复</span>
          <span>关于FIX</span>
          <span>加入我们</span>
        </div>
        <div class="search-content flex-h-center" v-if="this.searchShow">
          <el-input placeholder="请输入搜索内容" v-model="searchInfo">
          </el-input>
          <img @click="closeSearch()" src="./assets/images/search_icon_close_header.png" alt="">
        </div>
      </div>

    </div>
    <router-view/>
    <div class="bottom">
       <div class="left">
         ©COPYRIGHT <span class="time-color">FIX字幕侠2015-2017</span>  FIX字幕侠2015-2017 蜀ICP备17039209号
       </div>
       <div class="right"><div class="to-top fr">^</div><div class="desc fr">FIX字幕站 宅客ZHAIIKERdiv</div> </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      searchShow: false,
      searchInfo: ""
    };
  },
  mounted() {},
  methods: {
    getSearch() {
      this.searchShow = true;
    },
    closeSearch() {
      this.searchShow = false;
    }
  }
};
</script>

<style lang="scss" scoped>
html,body{
  min-width:1200px;
}
#app {
  width: 100%;
  .top-gap{
    height: 80px;
  }
  .top-nav {
    z-index: 3;
    padding: 5px 0;
    height: 70px;
    width: 100%;
    background-color: #000;
    position: fixed;
    top: 0;
    left: 0;
    min-width:1300px;
    .left-login-icon {
      width: 110px;
      height: 55px;
      margin-left: 6%;
      margin-top:7.5px;
      img {
        width: 100%;
        height: 100%;
      }
    }
    .right-nav-list {
      position: relative;
      height: 70px;
      margin-right: 6%;
      .nav-list {
        height: 70px;
        line-height: 70px;
        span {
          font-size: 24px;
          font-weight: bold;
          margin: 0 10px;
          color: #fff;
        }
      }
      .search-content {
        position: absolute;
        right: 0;
        top: 50%;
        transform: translateY(-50%);
        width: 200px;
        height: 32px;
        background-color: #fff;
        border-radius: 16px;
        overflow: hidden;
        img {
          width: 22px;
          height: 22px;
          margin-right: 5px;
        }
        /deep/ .el-input .el-input--suffix {
          height: 32px;
          line-height: 32px;

          /deep/ .el-input__inner {
            height: 32px;
            line-height: 32px;
            border: none !important;
          }
        }
      }
      .more-icon {
        height: 80px;
        width: 90px;
        .sina-out {
          width: 30px;
          height: 30px;
          float: left;
          img {
            width: 25px;
            height: 25px;
          }
          img:hover {
            width: 30px;
            height: 30px;
          }
        }

        .search-out {
          width: 30px;
          height: 30px;
          border-radius: 50%;
          background-color: #fff;
          img {
            width: 22px;
            height: 22px;
          }
        }
      }
    }
  }
  .bottom{
    width:100%;
    height: 80px;
    line-height: 80px;
    background-color: rgb(38, 38, 38);
    color:#fff;
    font-size:12px;
    margin-top:10px;
    .left{
      float:left;
      margin-left:6%;
      .time-color{
        color:rgb(255, 208, 0);
      }
    }
    .right{
      float:right;
      margin-right:6%;
      .to-top{
        font-size:20px;
        width:30px;
        height: 30px;
        background-color: rgb(8, 8, 8);
        margin-top:25px;
        line-height: 30px;
        text-align:center;
      }
      .to-top:hover{
         background-color:rgb(255, 208, 0);
      }
    }
  }
}
</style>
