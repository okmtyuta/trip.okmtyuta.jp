<script setup lang="ts">
import '@okmtyuta/awesome-css/reset.css'
</script>

<template>
  <header class="header">
    <!-- <div class="header-logo">trip.okmtyuta.jp</div>
    <div class="header-menu">
      <button>Home</button>
      <button>過去ログ</button>
    </div> -->
  </header>

  <main class="main">
    <div class="contents">
      <div class="me">
        <img alt="me" class="me-img" src="@/assets/me.jpg" />
      </div>
      <ul class="content-list">
        <li><a class="link" href="https://about.me.okmtyuta.jp">奥多摩に行った話</a></li>
        <li><a class="link" href="https://about.me.okmtyuta.jp">鎌倉に行った話</a></li>
      </ul>
    </div>
  </main>

  <footer class="footer"></footer>
</template>

<style scoped>
.me {
  display: flex;
  justify-content: center;
}
.me-img {
  border-radius: 4px;
}
.header {
  display: flex;
  justify-content: space-between;
}
.main {
  margin: 0 auto;
  padding: 0 24px;
  max-width: 860px;
}
.contents {
  gap: 20px;
}
.content-list {
  display: flex;
  flex-direction: column;
  gap: 8px;
}
.link {
  text-decoration: underline;
}
</style>
