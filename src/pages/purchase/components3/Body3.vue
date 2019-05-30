<template>
  <div class="container">
    <div class="row">
      <!-- 模态框 -->
      <div role="dialog" class="modal fad" id="layer">
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-head">
              <button type="button" class="close" data-dismiss="modal">
                <span>&times;</span>
              </button>
              <h4 class="modal-title">确定开车吗？</h4>
            </div>
            <div class="modal-body text-right">
              <button class="btn btn-primary" data-dismiss="modal">稍等</button>
              <button
                class="btn btn-danger"
                data-dismiss="modal"
                v-on:click="deleteMsg(nowIndex)"
              >出发</button>
            </div>
          </div>
        </div>
      </div>
      <div class="col-sm-6 col-md-3">
        <div class="thumbnail">
          <img src="../../../assets/img-purchase/q4.jpg">
          <div class="caption">
            <h3>嘿嘿嘿</h3>
            <p>
              <a
                href="#"
                class="btn btn-danger"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >开车</a>
              <a
                href="#"
                class="btn btn-default"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >按钮</a>
            </p>
          </div>
        </div>
      </div>
      <div class="col-sm-6 col-md-3">
        <div class="thumbnail">
          <img src="../../../assets/img-purchase/q4.jpg">
          <div class="caption">
            <h3>嘿嘿嘿</h3>
            <p>
              <a
                href="#"
                class="btn btn-danger"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >开车</a>
              <a
                href="#"
                class="btn btn-default"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >按钮</a>
            </p>
          </div>
        </div>
      </div>
      <div class="col-sm-6 col-md-3">
        <div class="thumbnail">
          <img src="../../../assets/img-purchase/q4.jpg">
          <div class="caption">
            <h3>嘿嘿嘿</h3>
            <p>
              <a
                href="#"
                class="btn btn-danger"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >开车</a>
              <a
                href="#"
                class="btn btn-default"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >按钮</a>
            </p>
          </div>
        </div>
      </div>
      <div class="col-sm-6 col-md-3">
        <div class="thumbnail">
          <img src="../../../assets/img-purchase/q4.jpg">
          <div class="caption">
            <h3>嘿嘿嘿</h3>
            <p>
              <a
                href="#"
                class="btn btn-danger"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >开车</a>
              <a
                href="#"
                class="btn btn-default"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >按钮</a>
            </p>
          </div>
        </div>
      </div>

      <div class="col-sm-6 col-md-3">
        <div class="thumbnail">
          <img src="../../../assets/img-purchase/q4.jpg">
          <div class="caption">
            <h3>嘿嘿嘿</h3>
            <p>
              <a
                href="#"
                class="btn btn-danger"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >开车</a>
              <a
                href="#"
                class="btn btn-default"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >按钮</a>
            </p>
          </div>
        </div>
      </div>
      <div class="col-sm-6 col-md-3">
        <div class="thumbnail">
          <img src="../../../assets/img-purchase/q4.jpg">
          <div class="caption">
            <h3>嘿嘿嘿</h3>
            <p>
              <a
                href="#"
                class="btn btn-danger"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >开车</a>
              <a
                href="#"
                class="btn btn-default"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >按钮</a>
            </p>
          </div>
        </div>
      </div>
      <div class="col-sm-6 col-md-3">
        <div class="thumbnail">
          <img src="../../../assets/img-purchase/q4.jpg">
          <div class="caption">
            <h3>嘿嘿嘿</h3>
            <p>
              <a
                href="#"
                class="btn btn-danger"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >开车</a>
              <a
                href="#"
                class="btn btn-default"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >按钮</a>
            </p>
          </div>
        </div>
      </div>
      <div class="col-sm-6 col-md-3">
        <div class="thumbnail">
          <img src="../../../assets/img-purchase/q4.jpg">
          <div class="caption">
            <h3>嘿嘿嘿</h3>
            <p>
              <a
                href="#"
                class="btn btn-danger"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >开车</a>
              <a
                href="#"
                class="btn btn-default"
                role="button"
                data-toggle="modal"
                data-target="#layer"
              >按钮</a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PurchaseBody3"
};
</script>

<style>
</style>