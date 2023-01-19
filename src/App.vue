<template>
  <div class="wrapper">
    <div class="position">
      <span class="iconfont" postion_icon>&#xe7f1;</span>
      北京理工大圩而国防科技园2号楼10层
      <span class="iconfont position_notice">&#xe7c4;</span>
    </div>
  </div>
  <div class="docker">
    <span class="docker_item docker_item--active">
      <div class="iconfont">&#xe7c6;</div>
      <div class="docker_title">首页</div>
    </span>
    <span class="docker_item">
      <div class="iconfont">&#xe698;</div>
      <div class="docker_title">购物车</div>
    </span>
    <span class="docker_item">
      <div class="iconfont">&#xe7b3;</div>
      <div class="docker_title">订单</div>
    </span>
    <span class="docker_item">
      <div class="iconfont">&#xe78b;</div>
      <div class="docker_title">我的</div>
    </span>
  </div>
</template>

<style lang="scss">
.wrapper{
  position: absolute;
  left: 0;
  top: 0;
  bottom: .5rem;
  right: 0;
}
.position{
  position: relative;
  padding: .16rem 0;
  line-height: .22rem;
  font-size: .16rem;
  .position_icon{
    top: .01rem;
    font-size: .2rem;
  }
  .position_notice{
    position: absolute;
    right: 0;
    top: .17rem;
    font-size: .2rem;
  }
  color: #333;
}
.docker{
  display: flex;
  box-sizing: border-box;
  position: absolute;
  padding: 0 .18rem;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 0.49rem;
  border-top: 1px #f1f1f1;
  background: green;
  &_item{
    flex: 1;
  text-align: center;
  .iconfont{
    margin: 0.07rem 0 0.02rem;
    font-size: .18rem;

  }
}

}
.docker_title{
  font-size: 20px;
  transform: scale(0.5 0.5);
  transform-origin: center top;
}
.docker_item--active{
  color: blue;
}
</style>
