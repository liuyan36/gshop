<template>
  <HeaderTop title="硅谷外卖会员卡">
    <router-link class="header_search" slot="left" to="/profile">
      <i class="iconfont icon-jiantou2"></i>
    </router-link>
  </HeaderTop>
</template>

<script>
import HeaderTop from "../../components/HeaderTop/HeaderTop";
export default {
  name: "GshopList",
  components: {
    HeaderTop
  }
};
</script>


<style lang="stylus" rel="stylesheet/stylus">
@import '../../common/stylus/mixins.styl';
.header_search {
      position: absolute;
    left: 15px;
    top: 50%;
    color: white;
    /* background-color: white; */
    -webkit-transform: translateY(-50%);
    transform: translateY(-50%);
    /* width: 10%; */
    height: 50%;
}
</style>
