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
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 2rem;
  padding: 2rem;
}

.rat-image {
  max-width: 90vw;
  max-height: 70vh;
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

.pgp-key {
  text-align: center;
}

.pgp-key pre {
  display: inline-block;
  text-align: left;
  background: rgba(0, 255, 0, 0.1);
  border: 1px solid #0f0;
  padding: 1rem;
  font-family: monospace;
  font-size: 0.75rem;
  color: #0f0;
  box-shadow: 0 0 10px rgba(0, 255, 0, 0.3);
  overflow-x: auto;
  max-width: 90vw;
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
  <div class="pgp-key">
<pre>
-----BEGIN PGP PUBLIC KEY BLOCK-----

xjMEYpv0lRYJKwYBBAHaRw8BAQdAcnRgNeX1IWnP8f6IvaWvpTyeIoYGCF4n
tUC7pKXX5wrNJXJhdHR1c0ByYXR0dXMub3JnIDxyYXR0dXNAcmF0dHVzLm9y
Zz7CjwQQFgoAIAUCYpv0lQYLCQcIAwIEFQgKAgQWAgEAAhkBAhsDAh4BACEJ
ELtN+Nxeis0JFiEEvFRUyEIqsSh/C9aeu0343F6KzQnALwEAwkl98ZxqGy+w
rj5hdNOmFKzD2jXul64/4cyaZ9Q0KIIA/3BuOzSvNAVDidzOaEtyadmhyHuD
ct7HIzp7LhgD5YMNzjgEYpv0lRIKKwYBBAGXVQEFAQEHQL40CqiewKBNnq/7
vCgRToGCLDNZSFubYWU5QZmktOoMAwEIB8J4BBgWCAAJBQJim/SVAhsMACEJ
ELtN+Nxeis0JFiEEvFRUyEIqsSh/C9aeu0343F6KzQkIJwEAvD1Y/BHbcurz
zl2J4QY32ajxnJUO1BX9BXhtrs1q/UoBAP1WGg1V2AVxpbKJf3HqRExTtO5Q
28VsWg95Op9wgl4C
=/9lA
-----END PGP PUBLIC KEY BLOCK-----
</pre>
  </div>
</div>
