<template>
  <div class="error-page">
    <img :src="imgLogin" alt="" />
    <el-link type="primary" :href="'/'">返回主页</el-link>
  </div>
</template>

<script>
import imgLogin from "@/assets/images/404.png";

export default {
  name: "error-page",
  data() {
    return {
      imgLogin,
    };
  },
};
</script>
<style lang="less" scoped>
.error-page {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  img {
    width: 50%;
  }
}
</style>
