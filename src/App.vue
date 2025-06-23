<script setup></script>

<template>
  <header>
    <nav>
      <ul>
        <li>
          <RouterLink to="/">ホーム</RouterLink>
        </li>
        <li>
          <RouterLink to="/about">このサイトについて</RouterLink>
        </li>
        <li>
          <RouterLink to="/links">リンク集</RouterLink>
        </li>
      </ul>
    </nav>
  </header>
  <RouterView></RouterView>
  <footer>
    <div class="copyright">
      <small>&copy; 2025 tatagon</small>
    </div>
  </footer>
</template>

<style scoped>
header {
  background-color: #42b983;
  padding: 10px 20px;
}
nav ul {
  list-style: none;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
  padding: 0;
  margin: 0;
}
nav li {
  display: inline;
}
nav a {
  color: white;
  text-decoration: none;
  font-size: 1.2rem;
}
nav a:hover {
  text-decoration: underline;
}
.copyright {
  color: white;
  text-align: center;
  margin-top: 80px;
  padding: 1em;
  box-sizing: border-box;
  background-color: #000;
}
.copyright small {
  font-size: 16px;
  font-weight: 500;
}
</style>
