<template>
  <div class="nuxt-app">
    <header>
      <Logo />
      <h1 class="title">nuxt-sub-app 123</h1>
    </header>
    <Nuxt />
  </div>
</template>

<style>
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.nuxt-app {
  margin: 0 auto;
  width: 400px;
}
</style>
<script>
export default {
  mounted() {
    console.log("subapp:", location.host);
  },
};
</script>
