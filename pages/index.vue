<template>
  <div class="container">
    <h1>Selamat datang di Berita Today</h1>
    <p>Situs berita terupdate dan terpercaya.</p>
    <div class="news-list">
      <div class="news-item">
        <h2>Judul Berita Pertama</h2>
        <p>Ini adalah cuplikan berita pertama.</p>
      </div>
      <div class="news-item">
        <h2>Judul Berita Kedua</h2>
        <p>Ini adalah cuplikan berita kedua.</p>
      </div>
      <div class="news-item">
        <h2>Judul Berita Ketiga</h2>
        <p>Ini adalah cuplikan berita ketiga.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // Kosongkan jika tidak ada logika khusus yang diperlukan
}
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
}

h1 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

p {
  font-size: 1rem;
  line-height: 1.5;
}

.news-list {
  margin-top: 2rem;
}

.news-item {
  border: 1px solid #ccc;
  padding: 1rem;
  margin-bottom: 1rem;
}

.news-item h2 {
  font-size: 1.5rem;
  margin-bottom: 0.5rem;
}

.news-item p {
  font-size: 1rem;
  line-height: 1.5;
}

</style>

