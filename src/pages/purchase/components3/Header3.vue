<template>
  <div>
    <nav class="navbar navbar-default">
      <div class="container-fluid">
        <!-- Brand and toggle get grouped for better mobile display -->
        <div class="navbar-header">
          <button
            type="button"
            class="navbar-toggle collapsed"
            data-toggle="collapse"
            data-target="#bs-example-navbar-collapse-1"
            aria-expanded="false"
          >
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">作业代做</a>
        </div>

        <!-- Collect the nav links, forms, and other content for toggling -->
        <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
          <ul class="nav navbar-nav">
            <li class="dropdown">
              <router-link to="/">
                <a href="#">
                  主页
                  <span class="sr-only">(current)</span>
                </a>
              </router-link>
            </li>
            <li class="dropdown">
              <router-link to="/new">消息</router-link>
            </li>
            <li class="active">
              <a
                class="dropdown-toggle"
                data-toggle="dropdown"
                role="button"
                aria-haspopup="true"
                aria-expanded="false"
              >
                下单
                <span class="caret"></span>
              </a>
              <ul class="dropdown-menu">
                <li class="dropdown">
                  <router-link to="/Purchase">
                    <a>大一作业入口</a>
                  </router-link>
                </li>
                <li>
                  <a href="#">大二作业入口</a>
                </li>
                <li>
                  <a href="#">大三作业入口</a>
                </li>
                <li role="separator" class="divider"></li>
                <li>
                  <a href="#">枪手入口</a>
                </li>
                <li role="separator" class="divider"></li>
                <li>
                  <a href="#">更多...</a>
                </li>
              </ul>
            </li>
          </ul>
          <form class="navbar-form navbar-left">
            <div class="form-group">
              <input type="text" class="form-control" placeholder="请输入要搜索的内容...">
            </div>
            <button type="submit" class="btn btn-default">搜索</button>
          </form>
          <ul class="nav navbar-nav navbar-right">
            <li>
              <a href="#">林林</a>
            </li>
            <li class="dropdown">
              <a
                href="#"
                class="dropdown-toggle"
                data-toggle="dropdown"
                role="button"
                aria-haspopup="true"
                aria-expanded="false"
              >
                当前状态
                <span class="caret"></span>
              </a>
              <ul class="dropdown-menu">
                <li>
                  <a href="#">登录</a>
                </li>
                <li>
                  <router-link to="/Register">
                    <a>退出</a>
                  </router-link>
                </li>
                <li>
                  <a href="#">联系我们</a>
                </li>
              </ul>
            </li>
          </ul>
        </div>
        <!-- /.navbar-collapse -->
      </div>
      <!-- /.container-fluid -->
    </nav>
  </div>
</template>

<script>
export default {
  name: "PurchaseHeader3"
};
</script>

<style>
</style>