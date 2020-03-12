<template>
  <div>
    <div>about页面</div>
    <nuxt-link :to="{path:'/news',query:{id:'666'}}">news页</nuxt-link>
    <nuxt-link :to="{path:'/'}">回主页</nuxt-link>
  </div>
</template>

<script>
export default {
  name: "news",
  components: {},
  mounted() {
    console.info(this.$route.params);
  }
};
</script>

<style>
</style>

