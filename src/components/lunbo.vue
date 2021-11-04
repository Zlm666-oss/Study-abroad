<template>
    <div class="main">
        <img src="http://cg.yuloo.com/images/banner1.jpg" alt="">
        <!-- 轮播图 -->
        <!-- <div class="swiper-container"> -->
            <!-- <div class="swiper-wrapper">
                <div class="swiper-slide">
                    <img src="http://cg.yuloo.com/images/banner1.jpg" alt="">
                </div>
                <div class="swiper-slide">
                    <img src="http://cg.yuloo.com/images/banner2.jpg" alt="">
                </div>
                <div class="swiper-slide">
                    <img src="http://cg.yuloo.com/images/banner3.jpg" alt="">
                </div>
            </div> -->
            <!-- 如果需要导航按钮 -->
            <!-- <div class="swiper-button-prev"></div>
            <div class="swiper-button-next"></div>
             -->
            <!-- 如果需要滚动条 -->
            <!-- <div class="swiper-scrollbar"></div> -->
        <!-- </div> -->
    </div>
</template>
<style lang="scss">
    .main{
        width: 100%;
        height: 1.1rem;
        img{
            width: 100%;
            height: 100%;
        }
    }
</style>
<script>
import Swiper from 'swiper';
export default {
    mounted(){
        new Swiper ('.swiper-container', {
        loop: true,
        // 如果需要前进后退按钮
        nextButton: '.swiper-button-next',
        prevButton: '.swiper-button-prev',
        // 如果需要滚动条
        scrollbar: '.swiper-scrollbar',
        })        
    }
}
</script>