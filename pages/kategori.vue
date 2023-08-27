<template>
  <div class="container">
    <h1>Kategori Berita</h1>
    <div class="kategori-list">
      <div class="kategori-box">
        <a href="#" class="kategori-link">Politik</a>
      </div>
      <div class="kategori-box">
        <a href="#" class="kategori-link">Teknologi</a>
      </div>
      <div class="kategori-box">
        <a href="#" class="kategori-link">Olahraga</a>
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

.kategori-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
}

.kategori-box {
  border: 1px solid #ddd;
  padding: 1.5rem;
  text-align: center;
  transition: transform 0.2s;
}

.kategori-box:hover {
  transform: translateY(-5px);
}

.kategori-link {
  color: #333;
  text-decoration: none;
  font-size: 1.2rem;
  transition: color 0.2s;
}

.kategori-box:hover .kategori-link {
  color: #007bff;
}
</style>
