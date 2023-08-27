<template>
  <header>
    <div class="logo">
      <img src="https://gitlab.com/DarvinExa/projek/-/raw/main/Berita_Today.png" alt="Logo Situs Berita" />
    </div>
    <nav>
      <ul>
        <li><a href="/">Beranda</a></li>
        <li><a href="/kategori">Kategori</a></li>
        <li><a href="/tentang">Tentang</a></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
header {
  background-color: #333;
  color: white;
  padding: 1rem;
  display: flex;
  align-items: center; /* Menyelaraskan elemen secara vertikal */
}

nav ul {
  list-style: none;
  padding: 0;
  display: flex;
  gap: 1rem;
}

nav ul li {
  margin: 0;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 1.2rem;
}

nav ul li a:hover {
  text-decoration: underline;
}

.logo {
  display: flex;
  align-items: center; /* Menyelaraskan elemen secara vertikal */
}

.logo img {
  max-width: 100px;
  margin-right: 2rem; /* Memberikan jarak antara logo dan menu */
}
</style>
