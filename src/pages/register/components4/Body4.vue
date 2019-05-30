<template>
  <div class="container">
    <div class="col-xs-1 col-xs-offset-9 aTopAndBottom">
      <a href data-toggle="modal" data-target="#login">
        <span class="glyphicon glyphicon-log-in"></span>
        <span id="loginText">登录</span>
      </a>
    </div>
    <!--注册按钮-->
    <div class="col-xs-1 aTopAndBottom">
      <a href data-toggle="modal" data-target="#register">
        <span class="glyphicon glyphicon-user"></span>
        <span id="registText">注册</span>
      </a>
    </div>
    <!-- 注册 -->
    <div id="register" class="modal fade" tabindex="-1">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-body">
            <button class="close" data-dismiss="modal">
              <span>&times;</span>
            </button>
          </div>
          <div class="modal-title">
            <h1 class="text-center">注册</h1>
          </div>
          <div class="modal-body">
            <form class="form-group" action>
              <div class="form-group">
                <label for>用户名</label>
                <input class="form-control" type="text" placeholder="6-15位字母或数字">
              </div>
              <div class="form-group">
                <label for>密码</label>
                <input class="form-control" type="password" placeholder="至少6位字母或数字">
              </div>
              <div class="form-group">
                <label for>再次输入密码</label>
                <input class="form-control" type="password" placeholder="至少6位字母或数字">
              </div>
              <div class="form-group">
                <label for>邮箱</label>
                <input class="form-control" type="email" placeholder="例如:***@***.com">
              </div>
              <div class="text-right">
                <button
                  class="btn btn-primary"
                  type="submit"
                  style="background-color: #3a8cd2b3;border: 0px solid transparent;"
                >提交</button>
                <button
                  class="btn btn-danger"
                  data-dismiss="modal"
                  style="background-color: #fb5e5999;border: 0px solid transparent;"
                >取消</button>
              </div>
              <a href data-toggle="modal" data-dismiss="modal" data-target="#login">
                <font style="font-size: 13px;">已有账号？点我登录</font>
              </a>
            </form>
          </div>
        </div>
      </div>
    </div>
    <!-- 注册 end-->
    <!-- 登录 -->
    <div id="login" class="modal fade">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-body">
            <button class="close" data-dismiss="modal">
              <span>&times;</span>
            </button>
          </div>
          <div class="modal-title">
            <h1 class="text-center">登录</h1>
          </div>
          <div class="modal-body">
            <form class="form-group" action>
              <div class="form-group">
                <label for>用户名</label>
                <input class="form-control" type="text" placeholder>
              </div>
              <div class="form-group">
                <label for>密码</label>
                <input class="form-control" type="password" placeholder>
              </div>
              <div class="text-right">
                <button
                  class="btn btn-primary"
                  type="submit"
                  style="background-color: #3a8cd2b3; border: 0px solid transparent;"
                >登录</button>
                <button
                  class="btn btn-danger"
                  data-dismiss="modal"
                  style="background-color: #fb5e5999;border: 0px solid transparent;"
                >取消</button>
              </div>
              <a href data-toggle="modal" data-dismiss="modal" data-target="#register">
                <font style="font-size: 13px;">还没有账号？点我注册</font>
              </a>
            </form>
          </div>
        </div>
      </div>
    </div>

    <div class="jumbotron">
      <h1>欢迎登录!</h1>
        <p>qaq</p>
      </div>
    </div>
</template>

<script>
export default {
  name: "RegisterBody4"
};
</script>

<style>

</style>
