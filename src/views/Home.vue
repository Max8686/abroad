<template>
  <div class="home">
    <Top />
    <Header/>
    <foots/>
    <footer>
      <div>
        <img src="../assets/scroll_02.png" alt="" />
        <span>电话咨询</span>
      </div>
      <div>
        <img src="../assets/scroll_01.png" alt="" />
        <span>在线咨询</span>
      </div>
      <div>
        <img src="../assets/scroll_03.png" alt="" />
        <span>网上报名</span>
      </div>
    </footer>
  </div>
</template>

<script>
import Top from "../components/top.vue";
import Header from "../components/header.vue";
import foots from '@/components/foots'
import Foots from '../components/foots.vue';
export default {
  name: "Home",
  components: {
    Top,
    Header,
    foots,
    Foots
  },
};

</script>
<style lang="less">
.home {
  height: 100%;
  width: 100%;
  position: relative;
  float: left;
  background: #eee;
  overflow: hidden;
  border-radius: 0.04rem;
  footer {
    display: flex;
    justify-content: space-around;
    font-size: 0.15rem;
    font-weight: 700;
    position: fixed;
    bottom: 0;
    width: 100%;
    div {
      width: 33%;
      background: #2b4d8b;
      text-align: center;
      color: white;
      padding: 0.1rem 0;
      // line-height: .4rem;
      display: flex;
      justify-content: space-around;
      align-content: center;
        span{
          
        text-overflow: ellipsis;
        white-space: nowrap;
        overflow: hidden;
        }
    }
  }
}
</style>
