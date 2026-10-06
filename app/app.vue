<template>
  <div class="page">
    <NuxtRouteAnnouncer />
    <main class="card">
      <h1 class="title">Welcome to Nuxt</h1>
      <p class="subtitle">
        Edit <code>app/app.vue</code> to get going dude.
      </p>
      <div class="actions">
        <a class="btn btn-primary" href="https://nuxt.com/docs" target="_blank" rel="noopener">Read the docs</a>
        <a class="btn btn-secondary" href="https://nuxt.com/modules" target="_blank" rel="noopener">Browse modules</a>
      </div>
    </main>
  </div>
</template>

<style>
:root {
  --purple: #7c3aed;
  --purple-dark: #2e1065;
  --pink: #ec4899;
  --yellow: #facc15;
  --text: #fdf4ff;
}

html,
body {
  margin: 0;
  font-family: system-ui, -apple-system, 'Segoe UI', Roboto, sans-serif;
  color: var(--text);
  background: var(--purple-dark);
}

.page {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 16px;
  box-sizing: border-box;
  background: linear-gradient(135deg, var(--purple-dark) 0%, var(--purple) 50%, var(--pink) 100%);
}

.card {
  max-width: 560px;
  width: 100%;
  padding: 48px 32px;
  border-radius: 24px;
  text-align: center;
  background: rgba(46, 16, 101, 0.6);
  border: 2px solid var(--yellow);
  box-shadow: 0 20px 60px rgba(236, 72, 153, 0.35);
}

.title {
  margin: 0 0 12px;
  font-size: clamp(2rem, 6vw, 3rem);
  color: var(--yellow);
}

.subtitle {
  margin: 0 0 32px;
  font-size: 1.1rem;
}

code {
  padding: 2px 8px;
  border-radius: 6px;
  background: var(--pink);
  color: #fff;
}

.actions {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  justify-content: center;
}

.btn {
  padding: 12px 24px;
  border-radius: 999px;
  font-weight: 600;
  text-decoration: none;
  transition: transform 0.15s ease;
}

.btn:hover {
  transform: translateY(-2px);
}

.btn-primary {
  background: var(--yellow);
  color: var(--purple-dark);
}

.btn-secondary {
  background: var(--pink);
  color: #fff;
}
</style>
