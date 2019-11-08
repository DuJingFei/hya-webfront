<template>
  <header class="home-header">
    <div class="main">
       <section class="logo">
        <img src="~/assets/images/se2.png" alt="hya-alt">
      </section>
      <nav>
        <li>产品</li>
        <li>行业方案</li>
        <li>客户成功</li>
        <li>服务与认证</li>
        <li>合作伙伴</li>
      </nav>
    </div>
  </header>
</template>
<script>
export default {
  name: "home-header",
  data() {
    return {};
  }
};
</script>
<style lang="less">
.home-header {
    display: flex;
    height: 60px;
    line-height: 60px;
    text-align: center;
    box-shadow: 0 1px 3px rgba(32,26,26,.1);
    background: #fff;
    .main {
      display: flex;
      width: 1200px;
      margin: 0 auto;
    }
    .logo {
      display: flex;
      align-items: center;
    }
    nav {
      overflow: hidden;
      > li {
        float: left;
        list-style-type: none;
        min-width: 100px;
        text-align: center;
        cursor: pointer;
      }
    }
}
</style>


