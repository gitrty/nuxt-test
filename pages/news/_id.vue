<template>
  <div>
    <div>new页面</div>
    <nuxt-link :to="{name:'about-id',params:{age:18}}">去about页</nuxt-link>
    <nuxt-link :to="{path:'/'}">会主页</nuxt-link>
  </div>
</template>

<script>
export default {
  name: "news",
  components: {},
  mounted() {
    console.info(this.$route.query);
  }
};
</script>

<style>
</style>

