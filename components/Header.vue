<template>
  <div class="hd">
    <h1 class="hd_title">Hello World!</h1>
    <ul class="hd_list">
      <nuxt-link class="hd_list__item" to="./">Home</nuxt-link>
      <nuxt-link class="hd_list__item" to="./link1">Link1</nuxt-link>
      <nuxt-link class="hd_list__item" to="./link2">Link2</nuxt-link>
    </ul>
  </div>
</template>
<style lang="scss">
.hd {
  width: 80%;
  margin: 0 auto;
  height: 80px;
  display: flex;
  align-items: center;
  &_title {
    display: inline;
    padding: 20px;
    margin: 0;
  }
  &_list {
    display: block;
    text-align: right;
    padding: 20px;
    &__item {
      padding: 0 20px;
      font-family: sans-serif;
      margin: 0;
      text-decoration: none;
      color: #333;
    }
  }
}
</style>