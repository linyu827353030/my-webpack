<template>
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-sm-2">
          <h6>six</h6>
        </div>

        <div class="col-sm-4">
          <h6>关于我们</h6>
          <p>专业你懂得</p>
        </div>

        <div class="col-sm-2">
          <h6>导航</h6>
          <ul class="unstyled">
            <li>主页</li>
            <li>服务</li>
            <li>链接</li>
            <li>联系我们</li>
          </ul>
        </div>

        <div class="col-sm-2">
          <h6>Follow us</h6>
          <ul class="unstyled">
            <li>微博</li>
            <li>微信</li>
            <li>来往</li>
          </ul>
        </div>

        <div class="col-sm-2">
          <h6>
            本网站由
            <span class="glyphicon glyphicon-heart"></span>Linlin制作
          </h6>
        </div>
      </div>
    </div>
  </footer>
  <!--页脚结束-->
</template>

<script>
export default {
  name: "PurchaseFooter3"
};
</script>

<style>
footer {
  background: #e7e7e7;
  color: #777;
  font-size: 16px;
  padding: 20px;
}
ul.unstyled {
  list-style: none;
  padding: 0;
  margin: 0;
}
footer h6 {
  color: #777;
}
</style>
