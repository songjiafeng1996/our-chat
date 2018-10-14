<template>
    <div class="box-detail banner-content">
        <div class="content clearfloat">
            <div class="title">
                马克西米利安：权力和爱情的游戏
            </div>
            <div class="center-title">
                马克西米利安：权力和爱情的游戏
            </div>
            <div class="out-img">
                <img src="../../assets/images/MAX.jpg" alt="">
            </div>
            <div class="all-info clearfloat">
                <div class="all-info-left fl">
                    <div class="title">
                        信息
                    </div>
                    <div class="play-info">

                        <p>
                            <span>播出网路：</span>
                            <span>ORF 1 (Austria/German)</span>
                        </p>
                        <p>
                            <span>播出时区:</span>
                            <span>Europe/Vienna</span>
                        </p>
                        <p>
                            <span>播出时间：</span>

                            <span class="activeColor">(剧终)</span>
                            <span>每周四 20:15 CEST</span>
                        </p>
                        <p>
                            <span>首播时间：：</span>
                            <span>2016-12-13</span>
                        </p>
                        <p class="name">F.I.X. 字幕侠</p>
                        <p class="name">除非特别说明，卡片中显示的时间均为您所在时区</p>

                    </div>
                </div>
                <div class="all-info-right fl">
                    <div class="top-no-info">
                        <div class="info">没有下一集信息</div>
                    </div>
                    <div class="recently-broadcast">
                        最近于 2017-03-04 （周六） 播出了 第1季 第3集 (Part 3)
                    </div>
                </div>
            </div>
            <div class="detail-movie-infos ">
                <p>导演: 安德烈亚斯·普罗查斯卡</p>
                <p>编剧: 马丁·安布罗希</p>
                <p>主演: 杰尼斯·纽沃纳</p>
                <p>类型: 劇情 Drama</p>
                <p>制片国家/地区: Austria</p>
                <p>语言: 德語 German</p>
                <p>首播: 2016-12-12</p>
                <p>集数: 3</p>
                <p>单集片长: 90分钟</p>
                <p>又名: 马克西米利安 / Maximilian – Das Spiel von Macht und Liebe</p>
                <p>IMDb链接:
                    <span class="link-color">tt5833846</span>
                </p>
                <p>【剧情简介】</p>
                <p>【资源下载】</p><span class="link-color">字幕下载</span>
                <p>E01<span class="link-color">字幕下载</span><span class="link-color">百度网盘</span><span class="link-color">电驴下载</span></p>
                <p>E02 字幕下载 <span class="link-color">百度网盘</span> 磁力下载 电驴下载</p>
                <p>E03 字幕下载 <span class="link-color">百度网盘</span> 磁力下载 电驴下载</p>

            </div>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.activeColor {
  color: red;
}
.box-detail {
  height: auto;
  /* background-color: pink; */
  margin-top: 50px;
  border: #ccc 1px solid;
  .content {
    margin: 50px;
    height: auto;
    width: 1100px;
    margin-bottom:60px;
    .title {
      font-size: 20px;
      font-weight: 300;
      height: 80px;
      left: 800px;
    }
    .center-title {
      font-size: 26px;
      font-weight: 500;
      text-align: center;
      height: 40px;
      left: 40px;
    }
    .out-img {
      width: 550px;
      margin: 20px auto 0;
      img {
        width: 550px;
        margin: 0 auto;
      }
    }
    .all-info {
      height: 260px;
      width: 100%;
      .all-info-left {
        width: 390px;
        height: 260px;
        .title {
          font-size: 28px;
          line-height: 80px;
          height: 80px;
          background-color: rgb(204, 216, 220);
          padding-left: 20px;
        }
        .play-info {
          p {
            height: 30px;
            line-height: 30px;
            padding-left: 20px;
          }
          .name {
            color: rgb(204, 216, 220);
          }
        }
      }
      .all-info-right {
        width: 710px;
        height: 260px;
        background-color: green;
        .top-no-info {
          height: 200px;
          width: 100%;
          background: #000;
          .info {
            font-size: 28px;
            color: #fff;
            text-align: center;
            height: 40px;
            line-height: 40px;
          }
        }
        .recently-broadcast {
          height: 60px;
          left: 60px;
          background-color: rgb(0, 176, 88);
          line-height: 60px;
          color: #fff;
          padding-left: 20px;
        }
      }
    }
    .all-info:hover {
      box-shadow: 5px 5px 5px 5px #ccc;
    }
    .detail-movie-infos{
        p{
            height: 26px;
            line-height:26px;
            font-size:14px;
            span{
                padding:0 10px;
            }
        }
        .link-color{
            color:rgb(255, 208, 0);
        }
    }
  }
}
</style>

