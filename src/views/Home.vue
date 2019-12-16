<template>
  <div class="home">
    <div class="top-nav">
      <div class="top-nav-left">
        <a class="top-nav-li" href="#">小米商城</a>
        <span class="division">|</span>
        <a class="top-nav-li" href="#">MIUI</a>
        <span class="division">|</span>
        <a class="top-nav-li" href="#">IoT</a>
        <span class="division">|</span>
        <a class="top-nav-li" href="#">云服务</a>
        <span class="division">|</span>
        <a class="top-nav-li" href="#">金融</a>
        <span class="division">|</span>
        <a class="top-nav-li" href="#">有品</a>
        <span class="division">|</span>
        <a class="top-nav-li" href="#">小爱开放平台</a>
        <span class="division">|</span>
        <a class="top-nav-li" href="#">企业团购</a>
        <span class="division">|</span>
        <a class="top-nav-li" href="#">资质证照</a>
        <span class="division">|</span>
        <a class="top-nav-li" href="#">协议规则</a>
        <span class="division">|</span>
        <a class="top-nav-li" href="#">下载app</a>
        <span class="division">|</span>
        <a class="top-nav-li" href="#">Select Location</a>
      </div>
      <div class="top-nav-right">
        <div class="login-wrapper">
          <a class="top-nav-li" href="#">登录</a>
          <span class="division login-division">|</span>
          <a class="top-nav-li" href="#">注册</a>
          <span class="division reg-division">|</span>
          <a class="top-nav-li message" href="#">消息通知</a>
        </div>
        <div class="shop-cart">
          <span class="iconfont-cart"></span>
          <span class="shop-cart-tit">购物车（0）</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home'
}
</script>

<style lang="scss" scope>
$navColor: #b0b0b0;

.iconfont-cart:before {
  content: "\E60C";
}
.iconfont-cart-plus:before {
  content: "\E60A";
}
.iconfont-cart-full:before {
  content: "\E60D";
}
.home {
  background: #333;
  .top-nav {
    width: 1226px;
    height: 40px;
    line-height: 40px;
    margin: 0 auto;
    font-size: 12px;
    .top-nav-li {
      color: $navColor;
    }
    .division {
      color: #424242;
      margin: 0 6.94px;
      font-family: sans-serif;
    }
    .top-nav-left {
      float: left;
    }
    .top-nav-right {
      float: right;
      .login-wrapper {
        float: left;
        margin-right: 25px;
        .message {
          padding-left: 3px;
        }
        .login-division {
          margin: 5px;
        }
        .reg-division {
          margin-left: 5px;
        }
      }
      .shop-cart {
        float: left;
        width: 120px;
        background: #424242;
        text-align: center;
        height: 40px;
        line-height: 40px;

        .iconfont-cart {
          color: $navColor;
          font-size: 20px;
          vertical-align: -4px;
          margin-right: 4px;
          line-height: 20px;
        }
        
        .shop-cart-tit {
          color: $navColor;
        }
      }
    }
  }
}
</style>
