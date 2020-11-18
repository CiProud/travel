<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe666;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe67d; </span>
      输入城市/景点/游玩/主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont arrow-icon">&#xe688;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "MyHeader",
};
</script>

<style scoped>
.header {
  --background-color: #00bcd4;
  font-size: 16px;
  line-height: 2.2rem;
  display: flex;
  background: var(--background-color, red);
  color: #fff;
}
.header .header-left {
  width: 2.2rem;
  text-align: center;
}
.header .header-input {
  flex: 1;
  height: 1.7rem;
  line-height: 1.7rem;
  background: #fff;
  border-radius: 0.3rem;
  margin-top: 0.25rem;
  margin-left: 0.3rem;
  color: #ccc;
  padding-left: 0.2rem;
}
.header .header-right {
  width: 3.1rem;
  text-align: center;
}
.back-icon {
  font-size: 1rem;
  text-align: center;
  display: block;
}
.arrow-icon {
  margin-left: -0.2rem;
}
</style>