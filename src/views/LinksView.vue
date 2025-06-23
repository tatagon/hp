<template>
  <div class="view-wrapper">
    <h1>Vue.js学習に役立つリンク集</h1>
    <ul :class="{ 'link-list': true }">
      <li><a href="https://vuejs.org/" target="_blank">公式サイト</a></li>
      <li><a href="https://vuejs.org/guide/" target="_blank">公式ガイド</a></li>
      <li><a href="https://vuejs.org/api/" target="_blank">APIリファレンス</a></li>
      <li><a href="https://router.vuejs.org/" target="_blank">Vue Router</a></li>
      <li><a href="https://vuex.vuejs.org/" target="_blank">Vuex</a></li>
      <li><a href="https://vuetifyjs.com/en/" target="_blank">Vuetify</a></li>
      <li><a href="https://vue-loader.vuejs.org/" target="_blank">Vue Loader</a></li>
    </ul>
  </div>
</template>

<style scoped>
.link-list {
  list-style-type: disc;
  padding-left: 1.5rem;
}
.link-list li {
  font-size: 1rem;
  margin-bottom: 0.5rem;
}
</style>
