# HyperFrames Motion Graphics Standard

HyperFrames is the programmatic GSAP + HTML motion graphics standard for generating animations, UI reveals, and video reels.

---

## 🎬 GSAP + CSS Motion Architecture

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>

<script>
  document.addEventListener("DOMContentLoaded", () => {
    const tl = gsap.timeline({ defaults: { ease: "power3.out", duration: 0.8 } });
    
    tl.from(".hero-title", { y: 40, opacity: 0, delay: 0.2 })
      .from(".hero-card", { scale: 0.95, opacity: 0, stagger: 0.15 }, "-=0.4")
      .from(".glow-accent", { opacity: 0, duration: 1.2 }, "-=0.6");
  });
</script>
```

---

## ⚡ Motion Tokens & Spring Curves

- **Fast Hover:** `all 0.2s cubic-bezier(0.4, 0, 0.2, 1)`
- **Smooth Modal/Drawer:** `transform 0.4s cubic-bezier(0.16, 1, 0.3, 1)`
- **Glow Pulse:** `@keyframes pulse { 0%, 100% { opacity: 0.4; } 50% { opacity: 0.8; } }`
