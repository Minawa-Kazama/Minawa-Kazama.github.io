<template>
  <div class="app">
    <header class="hero">
      <h1>Wandering Feather</h1>
      <p>When the stars fall silent, I still hear your name in the wind.</p>
    </header>

    <section class="gallery">
      <h2>Our Moments</h2>
      <div class="images">
        <img src="/images/love1.jpg" alt="Moment 1" />
      </div>
    </section>

    <section class="story">
      <h2>Little Love Stories</h2>
      <p>
        风间南羽轻轻靠在流浪者的肩上，耳边是他低低的嗓音与风吹过羽毛的声音。<br />
        “你是我在尘世间流浪千万里，只为找到的唯一归宿。”
      </p>
    </section>

    <footer>
      <p>© 2025 Wandering Feather. With love, always.</p>
    </footer>
  </div>
</template>

<style scoped>
.app {
  font-family: "Segoe UI", sans-serif;
  color: #f5f5f5;
  background: linear-gradient(to bottom, #1e1e2f, #2c3e50);
  min-height: 100vh;
  padding-bottom: 40px;
}

.hero {
  text-align: center;
  padding: 60px 20px;
  background: rgba(0, 0, 0, 0.4);
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
  font-weight: bold;
  letter-spacing: 2px;
}

.hero p {
  font-size: 1.2rem;
  opacity: 0.85;
}

.gallery {
  padding: 40px 20px;
  text-align: center;
}

.gallery h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.images {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 16px;
}

.images img {
  width: 240px;
  height: auto;
  border-radius: 16px;
  box-shadow: 0 4px 12px rgba(255, 255, 255, 0.1);
}

.story {
  padding: 40px 20px;
  text-align: center;
  max-width: 800px;
  margin: 0 auto;
}

.story h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.story p {
  font-size: 1.1rem;
  line-height: 1.8;
  white-space: pre-line;
}

footer {
  text-align: center;
  padding: 20px;
  font-size: 0.9rem;
  opacity: 0.6;
}
</style>
