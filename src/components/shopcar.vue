<template>
  <div>
    <div class="fanhui_cou">
      <div class="fanhui_1"></div>
      <div class="fanhui_ding">顶部</div>
    </div>
    <header class="header header_1">
      <div class="fix_nav">
        <div class="nav_inner">
          <a class="nav-left back-icon" href="javascript:history.back();">返回</a>
          <div class="tit">购物车</div>
        </div>
      </div>
    </header>
    <div class="container">
      <div class="row rowcar">
        <ul class="list-group">
          <li class="list-group-item text-primary">
            <div class="icheck pull-left mr5">
              <input type="checkbox" checked="checked" class="ids" prodStatus="1" itemkey>
              <label class="checkLabel">
                <span></span>
              </label>
            </div>朗尊软件
          </li>
          <li class="list-group-item hproduct clearfix">
            <div class="p-pic">
              <a href="/views/663">
                <img class="img-responsive" src="../assets/img/1787bd1d-9381-402b-b98e-97ceeddf7692.jpg">
              </a>
            </div>
            <div class="p-info">
              <a href="/views/663">
                <p class="p-title">艾吉贝2015新款多层收纳真皮单肩斜挎包女包头层牛皮斜跨小包包女</p>
              </a>
              <p class="p-attr">
                <span>颜色：红色；</span>
              </p>
              <p class="p-origin">
                <a
                  class="close p-close"
                  onclick="deleteShopCart('','艾吉贝2015新款多层收纳真皮单肩斜挎包女包头层牛皮斜跨小包包女','663','1358')"
                  href="javascript:void(0);"
                >×</a>
                <em class="price">¥179.00</em>
              </p>
            </div>
          </li>
          <li class="list-group-item clearfix">
            <div class="pull-left mt5">
              <span class="gary">小计：</span>
              <em class="red productTotalPrice">¥179.00</em>
            </div>
            <div class="btn-group btn-group-sm control-num">
              <a onclick="disDe(this)" href="javascript:void(0);" class="btn btn-default">
                <span class="glyphicon glyphicon-minus gary"></span>
              </a>
              <input
                type="tel"
                class="btn gary2 Amount"
                readonly="readonly"
                value="1"
                maxlength="4"
                itemkey
                prodId="663"
                skuId="1358"
              >
              <a onclick="increase(this)" href="javascript:void(0);" class="btn btn-default">
                <span class="glyphicon glyphicon-plus gary"></span>
              </a>
            </div>
          </li>
        </ul>
      </div>
    </div>
    <div class="fixed-foot">
      <div class="fixed_inner">
        <div class="pay-point">
          <div class="icheck pull-left mr10">
            <input type="checkbox" checked="checked" id="buy-sele-all" value="1">
            <label for="buy-sele-all">
              <span class="mt10"></span>全选
            </label>
          </div>
          <p>合计：
            <em class="red f22">¥
              <span id="totalPrice">179.00</span>
            </em>
          </p>
        </div>
        <div class="buy-btn-fix">
          <a href="javascript:submitShopCart();" class="btn btn-danger btn-buy">去结算</a>
        </div>
      </div>
    </div>
    <div class="clear"></div>

    <footer class="footer">
      <div class="foot-con">
        <div class="foot-con_2">
          <a href="index.html">
            <i class="navIcon home"></i>
            <span class="text">首页</span>
          </a>
          <a href="category.html">
            <i class="navIcon sort"></i>
            <span class="text">分类</span>
          </a>
          <a href="shopcart.html">
            <i class="navIcon shop"></i>
            <span class="text">购物车</span>
          </a>
          <a href="userhome.html">
            <i class="navIcon member"></i>
            <span class="text">我的</span>
          </a>
        </div>
      </div>
    </footer>
  </div>
</template>