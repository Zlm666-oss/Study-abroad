<template>
  <div class="home">
    <Header />
    <Head />
    <Lunbo />
    <div class="breadcrumb-bg">
      <div class="breadcrumb">
        当前位置：
        <a href="http://www.yuloo.com/">首页</a>&nbsp;&gt;&nbsp;
        <a href="http://cg.yuloo.com/">出国留学网</a>
      </div>
    </div>
    <Conent />
    <Chind/>
    <Hello />
    <Four />
  </div>
</template>

<script>
import Header from "@/components/header.vue";
import Head from "@/components/head.vue";
import Lunbo from "@/components/lunbo.vue";
import Chind from "@/views/chind/chind.vue";
import Conent from "@/components/conent.vue";
import Hello from "@/views/Hello/index.vue";
import Four from "@/views/four/four.vue";
export default {
  name: "Home",
  components: {
    Header,
    Head,
    Lunbo,
    Conent,
    Hello,
    Four,
    Chind,
  },
};
</script>
<style lang="scss">
.home {
  width: 100%;
  height: 100%;
  font-size: 0.14rem;
  display: flex;
  flex-direction: column;
  .breadcrumb-bg {
    background-color: #f5f7f9;
    padding: 10px 0 !important;
    .breadcrumb {
      font-size: 12px;
      line-height: 20px;
      color: #9fa9b3;
      background-color: #f5f7f9;
      margin-bottom: 0 !important;
      padding: 0 !important;
      a {
        font-size: 12px;
        line-height: 20px;
        color: #9fa9b3;
        background-color: #f5f7f9;
        margin-bottom: 0 !important;
        padding: 0 !important;
      }
    }
  }
}
</style>
