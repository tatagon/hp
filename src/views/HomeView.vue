<script setup>
import OfficialLink from '@/components/OfficialLink.vue'
</script>

<template>
  <div class="view-wrapper">
    <h1>HOME</h1>
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
  max-width: 600px;
  width: 100%;
  margin: auto;
}
h1 {
  color: #42b983;
  font-size: 2rem;
  margin-bottom: 20px;
  text-align: center;
}
.logo {
  text-align: center;
}
p {
  font-size: 1.2rem;
  margin-bottom: 10px;
}
</style>
