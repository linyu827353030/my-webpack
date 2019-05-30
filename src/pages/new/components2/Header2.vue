<template>
  <div class="container">
    <h1>抖图</h1>
    <nav class="navbar navbar-inverse">
      <div class="navbar-collapse">
        <ul class="nav navbar-nav navbar-left">
          <li>
            <router-link to="/">
              <a>主页</a>
            </router-link>
          </li>
          <li class="active">
            <router-link to="/new">
              <a href="#">抖一抖</a>
            </router-link>
          </li>
          <li>
            <router-link to="/purchase">
              <a href="#">抖友</a>
            </router-link>
          </li>
        </ul>
        <ul class="nav navbar-nav navbar-right">
          <li class>
            <router-link to="/register">
              <a href="#">登录</a>
            </router-link>
          </li>
          <li class>
            <a href="#">联系我们</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>


<script>
export default {
  name: "HomeHeader2"
};
</script>

<style>
</style>