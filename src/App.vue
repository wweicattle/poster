<template>
  <div id="app">
    <Poster />
    <a href="https://www.cnblogs.com/linfblog/p/12147432.html"></a>
    <a href="https://blog.csdn.net/weixin_42446516/article/details/104396425?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param"></a>
    <a href="./assets/logo.png" download="https://profile.csdnimg.cn/A/8/B/2_qq_40326098">sss
      <img border="0" src="./assets/logo.png" alt="runoob.com" />
    </a>
    <router-view />
  </div>
</template>
<script>
import Poster from "components/Poster";
export default {
  name: "App",
  data: function () {
    return {};
  },
  components: {
    Poster,
  },
};
</script>
<style lang="scss">
@import url(./assets/css/base.css);
</style>
