<template>
  <footer class="app-footer">
    <div class="container">
      <div class="profile">
        <img src="https://gitlab.com/DarvinExa/projek/-/raw/main/resident-evil-4-remake.jpg" alt="Profil Pembuat" />
        <div class="profile-info">
          <h3>Darvin Exaudi Simanjuntak</h3>
          <p>Tugas 2</p>
          <p>Email: pocongterbalik6@gmail.com</p>
        </div>
      </div>
      <div class="social-media">
        <h4>Sosial Media</h4>
        <ul>
          <li><a href="https://twitter.com" target="_blank">Twitter</a></li>
          <li><a href="https://www.facebook.com" target="_blank">Facebook</a></li>
          <li><a href="https://www.instagram.com" target="_blank">Instagram</a></li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.app-footer {
  background-color: #f5f5f5;
  padding: 2rem 0;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.profile {
  display: flex;
  align-items: center;
}

.profile img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  margin-bottom: 1rem;
  margin-right: 2rem;
}

.profile-info h3 {
  margin: 0;
}

.social-media h4 {
  margin: 0;
}

.social-media ul {
  list-style: none;
  padding: 0;
  display: flex;
}

.social-media ul li {
  margin-right: 1rem;
}

.social-media ul li a {
  color: #333;
  text-decoration: none;
}

.social-media ul li a:hover {
  text-decoration: underline;
}
</style>

