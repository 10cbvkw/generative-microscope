<template>
  <div id="app" class="main-container">
    <!-- 顶部导航栏 -->
    <header class="header">
      <nav class="nav-bar">
        <ul>
          <li><a href="https://example.com/document" target="_blank">Document</a></li>
          <li><a href="https://example.com/paper" target="_blank">Paper</a></li>
        </ul>
      </nav>
    </header>

    <!-- 中间GIF动图 -->
    <main class="main-content">
      <img src="../public/images/1.gif" alt="Generative Microscope Animation" class="gif-image" />
    </main>

    <!-- 底部超链接 -->
    <footer class="footer">
      <a href="https://bohrium.dp.tech/apps/vem-dps" target="_blank" class="footer-link">vEM app</a>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HomePage",
};
</script>

<style scoped>
.main-container {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: space-between;
  align-items: center;
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}

.header {
  width: 100%;
  background-color: #333;
  padding: 1rem;
}

.nav-bar ul {
  list-style: none;
  display: flex;
  justify-content: flex-start;
  margin: 0;
  padding: 0;
}

.nav-bar li {
  margin-right: 2rem;
}

.nav-bar a {
  text-decoration: none;
  color: white;
  font-size: 1.2rem;
}

.main-content {
  flex-grow: 1;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
}

.gif-image {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

.footer {
  padding: 1rem;
  text-align: center;
}

.footer-link {
  text-decoration: none;
  color: #333;
  font-size: 1.5rem;
}
</style>