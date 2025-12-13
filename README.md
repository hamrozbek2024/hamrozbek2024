<!-- ===== Animated Name for README ===== -->
<h1 align="center">
  <span class="glow-name">👋 Hi, I'm Hamrozbek</span>
</h1>

<p align="center">
  🚀 Fullstack Developer | Backend & System Design Enthusiast
</p>

<style>
.glow-name {
  font-size: 42px;
  font-weight: 800;
  background: linear-gradient(
    90deg,
    #00eaff,
    #7cff00,
    #ff00cc,
    #00eaff
  );
  background-size: 300% auto;
  color: transparent;
  -webkit-background-clip: text;
  animation:
    gradientMove 4s linear infinite,
    glowPulse 2s ease-in-out infinite,
    blinkSoft 3s infinite;
}

/* Gradient harakati */
@keyframes gradientMove {
  0% { background-position: 0% center; }
  100% { background-position: 300% center; }
}

/* Glow effekti */
@keyframes glowPulse {
  0% {
    text-shadow: 0 0 6px #00eaff;
  }
  100% {
    text-shadow:
      0 0 12px #00eaff,
      0 0 24px #7cff00,
      0 0 40px #ff00cc;
  }
}

/* Yengil miltillash */
@keyframes blinkSoft {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.85; }
}
</style>
<!-- ===== End ===== -->
