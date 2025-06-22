<script setup>
import OfficialLink from '@/components/OfficialLink.vue'
</script>

<template>
  <div class="view-wrapper">
    <h1>HOME Vue3</h1>
    <p>
      <img src="@/assets/logo.svg" alt="Vueのロゴ画像" width="100" />
    </p>
    <ul>
      <li>
        <RouterLink to="/about">このサイトは何？</RouterLink>
      </li>
      <li>
        <RouterLink to="/links">ページ集へ</RouterLink>
      </li>
    </ul>
    <OfficialLink></OfficialLink>
  </div>
</template>

<style>
.view-wrapper {
  padding: 20px;
}
h1 {
  color: #42b983;
  font-size: 2rem;
  margin-bottom: 20px;
}
p {
  font-size: 1.2rem;
  margin-bottom: 10px;
}
</style>
