<template>
  <div class="container">
    <div class="col-md-3">
      <h2>如何抖图？</h2>
      <ul class="nav nav-tabs nav-stacked">
        <li>
          <a href="#">某大学大神现场教抖图...</a>
        </li>
        <li>
          <a href="#">某某某抖图怎么怎么不得了...</a>
        </li>
        <li>
          <a href="#">某社区出现惊天的抖友...</a>
        </li>
        <li>
          <a href="#">抖图对健康的好处...</a>
        </li>
        <li>
          <a href="#">抖逗逗...</a>
        </li>
        <li>
          <a href="#">抖逗逗...</a>
        </li>
        <li>
          <a href="#">抖逗逗...</a>
        </li>
        <li>
          <a href="#">抖逗逗...</a>
        </li>
        <li>
          <a href="#">抖逗逗...</a>
        </li>
        <li>
          <a href="#">抖逗逗...</a>
        </li>
        <li>
          <a href="#">抖逗逗...</a>
        </li>
      </ul>
    </div>
    <div class="col-md-6" >
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
    <div class="col-md-3">
      <h2>如何成为抖人？</h2>
      <ul class="nav nav-tabs nav-stacked">
        <li>
          <a href="#">抖友修炼秘诀...</a>
        </li>
        <li>
          <a href="#">怎么怎么不得了...</a>
        </li>
        <li>
          <a href="#">怎么怎么牛批...</a>
        </li>
        <li>
          <a href="#">玫瑰花瓣...</a>
        </li>
        <li>
          <a href="#">一片一片掉落...</a>
        </li>
        <li>
          <a href="#">是你的聚散..</a>
        </li>
        <li>
          <a href="#">sad撒多...</a>
        </li>
        <li>
          <a href="#">sad撒大所多撒大所多...</a>
        </li>
        <li>
          <a href="#">抖逗烦得很女男女逗...</a>
        </li>
        <li>
          <a href="#">抖萨达萨达逗逗...</a>
        </li>
        <li>
          <a href="#">抖逗逗...</a>
        </li>
      </ul>
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
        loop: "true"
      }
    };
  }
};
</script>

<style>
a {
  color: #ccc;
}
.swiper-pagination-bullet-active {
  background-color: #fff;
}
.col-md-2 {
  color: #ccc;
}
</style>
