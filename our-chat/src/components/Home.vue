<template>
  <div class="home-content">
    <div class="top-nav-content">
      <div class="gap"></div>
      <div class="title">
        FIX作品
      </div>
      <div class="line"></div>
      <div class="banner-content">
        <div class="nav-list">
          <span>ALL</span>
          <span>FIX德语社</span>
          <span>欧美剧集</span>
          <span>欧美电影</span>
          <span>ALL</span>
          <span>FIX德语社</span>
          <span>欧美剧集</span>
          <span>欧美电影</span>
        </div>
      </div>
    </div>
    <div class="main-content-list clearfloat banner-content">
      <div class="list-item fl" id="mouseBox">
        <div class="out-img">
          <img class="bg" src="../assets/images/MAX.jpg" alt="马克西米利安：权力和爱情的游戏">
          <div class="action-play">
            <router-link to="/detail">
              <img class="play" src="../assets/images/play.png" alt="">
            </router-link>
          </div>
        </div>
        <div class="out-movie-name">
          <div class="movie-name">
            马克西米利安：权力和爱情的游戏力和爱情的游戏
          </div>
        </div>
        <div class="line-bottom"></div>
        <div class="cinema">FIX德语社</div>
      </div>
      <div class="list-item fl" id="mouseBox">
        <div class="out-img">
          <img class="bg" src="../assets/images/MAX.jpg" alt="马克西米利安：权力和爱情的游戏">
          <div class="action-play">
            <router-link to="/detail">
              <img class="play" src="../assets/images/play.png" alt="">
            </router-link>
          </div>
        </div>
        <div class="out-movie-name">
          <div class="movie-name">
            马克西米利安：权力和爱情的游戏力和爱情的游戏
          </div>
        </div>
        <div class="line-bottom"></div>
        <div class="cinema">FIX德语社</div>
      </div>
      <div class="list-item fl" id="mouseBox">
        <div class="out-img">
          <img class="bg" src="../assets/images/MAX.jpg" alt="马克西米利安：权力和爱情的游戏">
          <div class="action-play">
            <img class="play" src="../assets/images/play.png" alt="">
          </div>
        </div>
        <div class="out-movie-name">
          <div class="movie-name">
            马克西米利安：权力和爱情的游戏力和爱情的游戏
          </div>
        </div>
        <div class="line-bottom"></div>
        <div class="cinema">FIX德语社</div>
      </div>
      <div class="list-item fl" id="mouseBox">
        <div class="out-img">
          <img class="bg" src="../assets/images/MAX.jpg" alt="马克西米利安：权力和爱情的游戏">
          <div class="action-play">
            <img class="play" src="../assets/images/play.png" alt="">
          </div>
        </div>
        <div class="out-movie-name">
          <div class="movie-name">
            马克西米利安：权力和爱情的游戏力和爱情的游戏
          </div>
        </div>
        <div class="line-bottom"></div>
        <div class="cinema">FIX德语社</div>
      </div>
      <div class="list-item fl" id="mouseBox">
        <div class="out-img">
          <img class="bg" src="../assets/images/MAX.jpg" alt="马克西米利安：权力和爱情的游戏">
          <div class="action-play">
            <img class="play" src="../assets/images/play.png" alt="">
          </div>
        </div>
        <div class="out-movie-name">
          <div class="movie-name">
            马克西米利安：权力和爱情的游戏力和爱情的游戏
          </div>
        </div>
        <div class="line-bottom"></div>
        <div class="cinema">FIX德语社</div>
      </div>
      <div class="list-item fl" id="mouseBox">
        <div class="out-img">
          <img class="bg" src="../assets/images/MAX.jpg" alt="马克西米利安：权力和爱情的游戏">
          <div class="action-play">
            <img class="play" src="../assets/images/play.png" alt="">
          </div>
        </div>
        <div class="out-movie-name">
          <div class="movie-name">
            马克西米利安：权力和爱情的游戏力和爱情的游戏
          </div>
        </div>
        <div class="line-bottom"></div>
        <div class="cinema">FIX德语社</div>
      </div>
      <div class="list-item fl" id="mouseBox">
        <div class="out-img">
          <img class="bg" src="../assets/images/MAX.jpg" alt="马克西米利安：权力和爱情的游戏">
          <div class="action-play">
            <img class="play" src="../assets/images/play.png" alt="">
          </div>
        </div>
        <div class="out-movie-name">
          <div class="movie-name">
            马克西米利安：权力和爱情的游戏力和爱情的游戏
          </div>
        </div>
        <div class="line-bottom"></div>
        <div class="cinema">FIX德语社</div>
      </div>

      <div class="list-item fl" id="mouseBox">
        <div class="out-img">
          <img class="bg" src="../assets/images/MAX.jpg" alt="马克西米利安：权力和爱情的游戏">
          <div class="action-play">
            <img class="play" src="../assets/images/play.png" alt="">
          </div>
        </div>
        <div class="out-movie-name">
          <div class="movie-name">
            马克西米利安：权力和爱情的游戏力和爱情的游戏
          </div>
        </div>
        <div class="line-bottom"></div>
        <div class="cinema">FIX德语社</div>
      </div>
    </div>
    <div class="paging">
      <el-pagination background layout="prev, pager, next" :total="50">
      </el-pagination>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      mouseClass: false
    };
  },
  mounted() {},
  methods: {}
};
</script>


<style scoped lang="scss">
.home-content {
  width: 100%;
  height: auto;
  .top-nav-content {
    height: 370px;
    width: 100%;
    background-color: #000;
    .gap {
      height: 100px;
    }
    .title {
      height: 80px;
      margin-top: 80px;
      text-align: center;
      line-height: 80px;
      font-size: 58px;
      color: #fff;
      font-weight: bold;
    }
    .line {
      width: 140px;
      height: 1px;
      background-color: #fff;
      margin: 0 auto;
    }
    .nav-list {
      height: 60px;
      line-height: 60px;
      float: left;
      margin-top: 50px;
      span {
        color: #fff;
        font-size: 16px;
        margin-right: 10px;
      }
    }
  }
  .main-content-list {
    height: auto;
    margin-top: 40px;
    .list-item {
      width: 285px;
      height: 530px;
      margin-right: 20px;
      margin-bottom: 20px;
      float: left;
      .out-img {
        width: 285px;
        height: 400px;
        overflow: hidden;
        position: relative;
        .action-play {
          position: absolute;
          top: 0;
          left: 0;
          right: 0;
          bottom: 0;
          background-color: rgba(204, 204, 204, 0.5);
          display: none;
          .play {
            width: 50px;
            height: 50px;
            position: absolute;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
          }
        }

        .bg {
          width: 100%;
          height: 100%;
          transition: all 1.2s;
        }
        .bg:hover {
          transform: scale(1.2);
          width: 100%;
          height: 100%;
        }
      }
      .out-img:hover .action-play {
        display: block;
      }
      .out-img:hover .bg {
        transform: scale(1.2);
        width: 100%;
        height: 100%;
      }
      .out-movie-name {
        height: auto;
        .movie-name {
          font-size: 16px;
          width: 95%;
          line-height: 30px;
          margin: 10px auto;
          text-align: center;
          color: #333;
        }
      }

      .line-bottom {
        height: 2px;
        width: 80px;
        margin: 0 auto 10px;
        background-color: #ffd000;
      }
      .cinema {
        height: 30px;
        line-height: 30px;
        font-size: 12px;
        color: #ccc;
        text-align: center;
      }
    }
    .list-item:nth-child(4n + 4) {
      margin-right: 0;
    }
  }
  .paging {
    margin: 50px auto 10px;
    width: 200px;
  }
}
</style>
