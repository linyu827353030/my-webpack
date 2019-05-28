<template>
  <div class="row">
    <div class="col-md-2">
      <div class="row">
        <div class="alert alert-danger alert-dismissible" role="alert">
            <button type="button" onclick="this.parentNode.parentNode.removeChild(this.parentNode);" class="close" data-dismiss="alert">
                <span aria-hidden="true">×</span>
                <span class="sr-only">Close</span></button>
            <strong>
                <i class="fa fa-warning"></i>关于我们!</strong>
            <marquee>
                <p style="font-family: Impact; font-size: 18pt">我们非常牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批牛批!</p></marquee>
        </div>
    </div>
    </div>
    <div class="col-md-8">
      <swiper :options="swiperOption">
        <!-- slides -->
        <swiper-slide>
          <img
            class="img-responsive center-block"
            src="../../../assets/img-swiper/background01.jpg"
          >
        </swiper-slide>
        <swiper-slide>
          <img
            class="img-responsive center-block"
            src="../../../assets/img-swiper/background02.jpg"
          >
        </swiper-slide>
        <swiper-slide>
          <img
            class="img-responsive center-block"
            src="../../../assets/img-swiper/background03.jpg"
          >
        </swiper-slide>
        <swiper-slide>
          <img
            class="img-responsive center-block"
            src="../../../assets/img-swiper/background04.jpg"
          >
        </swiper-slide>
        <!-- Optional controls -->
        <div class="swiper-pagination" slot="pagination"></div>
        <!-- <div class="swiper-button-prev" slot="button-prev"></div>
        <div class="swiper-button-next" slot="button-next"></div>-->
        <!-- <div class="swiper-scrollbar" slot="scrollbar"></div> -->
      </swiper>
    </div>
    <div class="col-md-2">
      我们专业我们专业我们专业我们专业
      <hr>
      我们xxxxxxxxxxxxxxxxxxxxxxxxxx
       <hr>
      我们xxxxxxxxxxxxxxxxxxxxxxxxxx
       <hr>
      我们xxxxxxxxxxxxxxxxxxxxxxxxxx
       <hr>
      我们xxxxxxxxxxxxxxxxxxxxxxxxxx
       <hr>
      我们xxxxxxxxxxxxxxxxxxxxxxxxxx
       <hr>
      我们xxxxxxxxxxxxxxxxxxxxxxxxxx
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeSwiper",
  data() {
    return {
      swiperOption: {
        pagination: ".swiper-pagination",
        loop: 'true'
      }
    };
  }
};
</script>

<style>
.swiper-pagination-bullet-active {
  background-color: #fff;
}
.col-md-2{
  color: #ccc
}
</style>
