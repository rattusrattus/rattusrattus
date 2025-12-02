---
layout: default
title: rattus.org
---

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body, html {
  background: #000;
  overflow-x: hidden;
}

.cyber-page {
  min-height: 100vh;
  background: #000;
  display: flex;
  align-items: center;
  justify-content: center;
}

.rat-image {
  max-width: 90vw;
  max-height: 90vh;
  border: 2px solid #0f0;
  box-shadow:
    0 0 20px rgba(0, 255, 0, 0.5),
    0 0 40px rgba(0, 255, 0, 0.3),
    0 0 60px rgba(0, 255, 0, 0.1);
  animation: pulse-glow 3s ease-in-out infinite;
}

@keyframes pulse-glow {
  0%, 100% {
    box-shadow:
      0 0 20px rgba(0, 255, 0, 0.5),
      0 0 40px rgba(0, 255, 0, 0.3),
      0 0 60px rgba(0, 255, 0, 0.1);
  }
  50% {
    box-shadow:
      0 0 30px rgba(0, 255, 0, 0.7),
      0 0 60px rgba(0, 255, 0, 0.5),
      0 0 90px rgba(0, 255, 0, 0.3);
  }
}

.scanlines {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  background: repeating-linear-gradient(
    0deg,
    rgba(0, 0, 0, 0.1) 0px,
    rgba(0, 0, 0, 0.1) 1px,
    transparent 1px,
    transparent 2px
  );
  z-index: 100;
}
</style>

<div class="scanlines"></div>
<div class="cyber-page">
  <img src="/assets/cyber-rat.jpg" alt="Cyber Rat" class="rat-image">
</div>
