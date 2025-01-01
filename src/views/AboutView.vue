<template>
  <div class="about">
    <h1>关于我</h1>
    <a-button type="primary" @click="goHome">返回首页</a-button>
    <icon-user />
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
