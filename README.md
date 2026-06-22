<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                        HERO SECTION                           -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=🔥%20FIREBALL%20XR&fontSize=70&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Conjure%20Fire%20With%20Your%20Bare%20Hands&descAlignY=60&descSize=20" width="100%" />

<br />

# ✨ Fireball XR

### _A real-time hand-tracking spell-casting experience powered by computer vision and WebGL_

<br />

[![JavaScript](https://img.shields.io/badge/JavaScript-ES2022-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Three.js](https://img.shields.io/badge/Three.js-r165-000000?style=for-the-badge&logo=threedotjs&logoColor=white)](https://threejs.org/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-Hands-0097A7?style=for-the-badge&logo=google&logoColor=white)](https://mediapipe.dev/)
[![WebGL](https://img.shields.io/badge/WebGL-2.0-990000?style=for-the-badge&logo=webgl&logoColor=white)](https://www.khronos.org/webgl/)
[![Web Audio API](https://img.shields.io/badge/Web%20Audio-API-FF6B35?style=for-the-badge&logo=googlechrome&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<br />

[![Stars](https://img.shields.io/github/stars/yourusername/fireball-xr?style=social)](https://github.com/yourusername/fireball-xr/stargazers)
[![Forks](https://img.shields.io/github/forks/yourusername/fireball-xr?style=social)](https://github.com/yourusername/fireball-xr/network/members)
[![Issues](https://img.shields.io/github/issues/yourusername/fireball-xr?style=flat-square&color=ff6b35)](https://github.com/yourusername/fireball-xr/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](CONTRIBUTING.md)
[![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=flat-square)](https://github.com/yourusername/fireball-xr)

<br />

---

<!-- Demo Banner Placeholder -->
> 🖼️ **[DEMO GIF PLACEHOLDER]**
> _Replace this section with your recorded screen capture showing the fireball in action_

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│          🎥  LIVE DEMO GIF  —  Replace Me!                  │
│                                                             │
│     [ Hand tracking → Fist closed → 🔥 Fireball grows ]    │
│     [ Fist opens → 💥 Massive explosion detonates!   ]     │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

**[🚀 Try it Live →](https://yourusername.github.io/fireball-xr)** &nbsp;|&nbsp; **[📹 Watch Demo →](#screenshots)** &nbsp;|&nbsp; **[📖 Read Docs →](#-how-it-works)**

<br />

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                       OVERVIEW                                -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🌋 Overview

**Fireball XR** transforms your browser into a magical arena where your hands are the wand. Using your device's camera and Google's MediaPipe Hands model, the app tracks 21 skeletal landmarks on your hand in real time — all processed locally on-device with zero server calls.

Close your fist and watch a living, breathing fireball ignite at your knuckles, pulsing with layered flame geometry, dynamic particle jets, and a heat-distortion halo that swells as you charge it. Release your grip — and unleash a catastrophic explosion complete with shockwave rings, volumetric smoke billows, cascading ember showers, and bone-rattling synthesized audio. The entire visual stack is rendered through a **Three.js WebGL pipeline** at silky 60 fps, with GPU-accelerated particle systems and procedural audio crafted via the Web Audio API.

> **No plugins. No downloads. No backend. Just your hand, your camera, and pure JavaScript magic.**

<div align="center">

```
  👋  Open hand → idle state     ✊  Closed fist → charging...     💥  Release → EXPLOSION!
```

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                       FEATURES                                -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## ⚡ Features

<div align="center">

| 🖐️ **Real-Time Hand Tracking** | ✊ **Fist Detection** | 🔥 **Dynamic Fireball Growth** |
|:---:|:---:|:---:|
| 21-point MediaPipe skeletal model runs entirely in-browser at 30+ fps | Finger-curl landmark algorithm distinguishes open vs. closed gestures with high accuracy | Fireball radius, brightness, and turbulence scale continuously as you hold the fist |

| 💥 **Explosion System** | 🌟 **Particle Effects** | 🌫️ **Smoke Simulation** |
|:---:|:---:|:---:|
| Multi-ring shockwave burst with radial debris and screen-flash on fist release | GPU-driven point-cloud sparks and ember jets with randomized velocity and decay curves | Layered translucent smoke sprites that billow outward post-explosion with fade physics |

| 🔊 **Audio Feedback** | 📳 **Camera Shake** | 📐 **Responsive UI** |
|:---:|:---:|:---:|
| Procedural synthesized crackle, whoosh, and detonation boom via Web Audio API oscillators | Viewport trauma effect on explosion — the world shudders on impact | Adapts to any screen size; overlay HUD elements scale for desktop, tablet, and mobile |

| 🐛 **Debug Panel** | 🎨 **Layered Flame Geometry** | ⚙️ **Zero-Dependency Core** |
|:---:|:---:|:---:|
| Live overlay showing landmark coordinates, charge level, FPS, and gesture state | Six discrete Three.js mesh layers compose a physically convincing fire sphere | Pure HTML + CSS + JS — no build step, no bundler, no framework overhead |

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                       TECH STACK                              -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology | Purpose |
|:------|:-----------|:--------|
| **Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | App shell, styling, and all runtime logic |
| **Computer Vision** | ![MediaPipe](https://img.shields.io/badge/MediaPipe%20Hands-0097A7?style=flat-square&logo=google&logoColor=white) | Real-time 21-landmark hand skeleton detection |
| **3D Graphics** | ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white) | WebGL scene, meshes, materials, lighting, and camera |
| **GPU Rendering** | ![WebGL](https://img.shields.io/badge/WebGL%202.0-990000?style=flat-square&logo=webgl&logoColor=white) | Hardware-accelerated particle systems and shader rendering |
| **Audio** | ![Web Audio API](https://img.shields.io/badge/Web%20Audio%20API-FF6B35?style=flat-square&logo=googlechrome&logoColor=white) | Procedural synth — crackle, charge hum, and explosion boom |
| **Browser APIs** | ![getUserMedia](https://img.shields.io/badge/getUserMedia-Camera-4CAF50?style=flat-square&logo=googlechrome&logoColor=white) | Live video stream from device camera |
| **CDN Delivery** | ![jsDelivr](https://img.shields.io/badge/jsDelivr-CDN-E84D3D?style=flat-square&logo=jsdelivr&logoColor=white) | Zero-install script delivery for Three.js and MediaPipe |

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                      ARCHITECTURE                             -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🏗️ Architecture

```
┌──────────────────────────────────────────────────────────────────────┐
│                         FIREBALL XR  —  Pipeline                     │
└──────────────────────────────────────────────────────────────────────┘

         📷  USER CAMERA
              │
              │  MediaStream (getUserMedia)
              ▼
    ┌─────────────────────┐
    │   MediaPipe Hands   │  ← WASM model, runs fully on-device
    │  (21 Landmarks/Hand)│
    └────────┬────────────┘
             │  x, y, z coordinates @ 30 fps
             ▼
    ┌─────────────────────┐
    │  Gesture Detection  │  ← Finger-curl algorithm
    │  • Fist / Open hand │     landmark[4] vs landmark[8..20]
    │  • Wrist position   │     screen-space mapping
    └────────┬────────────┘
             │  isFist: bool | chargeLevel: float
             ▼
    ┌─────────────────────┐
    │   Fireball Logic    │  ← State machine
    │  • IDLE             │     charge accumulator
    │  • CHARGING         │     blast threshold
    │  • EXPLODING        │
    └────────┬────────────┘
             │  scale, position, blastEvent
             ▼
    ┌─────────────────────┐        ┌────────────────────┐
    │  Three.js Renderer  │───────▶│   Web Audio API    │
    │  • Scene graph      │        │  Crackle oscillator│
    │  • Perspective cam  │        │  Charge hum        │
    │  • WebGL canvas     │        │  Explosion boom    │
    └────────┬────────────┘        └────────────────────┘
             │
             ▼
    ┌─────────────────────┐
    │   Visual Effects    │
    │  • Flame layers ×6  │
    │  • Heat ring        │
    │  • Spark particles  │
    │  • Shockwave rings  │
    │  • Smoke sprites    │
    │  • Dynamic lighting │
    │  • Camera shake     │
    └─────────────────────┘
```

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     HOW IT WORKS                              -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🎮 How It Works

```
  STEP 1          STEP 2          STEP 3          STEP 4
┌─────────┐    ┌─────────┐    ┌─────────┐    ┌─────────┐
│  Open   │    │ Camera  │    │  Close  │    │Fireball │
│   App   │───▶│Enabled  │───▶│  Fist   │───▶│ Ignites │
│         │    │         │    │   ✊    │    │  🔥🔥  │
└─────────┘    └─────────┘    └─────────┘    └────┬────┘
                                                   │
  STEP 7          STEP 6          STEP 5           │
┌─────────┐    ┌─────────┐    ┌─────────┐         │
│ Scene   │    │  BOOM!  │    │ Open    │         │
│Resets✨ │◀───│  💥💥   │◀───│  Hand  │◀────────┘
│         │    │  BLAST! │    │   🖐️   │  Charge
└─────────┘    └─────────┘    └─────────┘  Grows!
```

| Step | Action | What Happens Under the Hood |
|:----:|:-------|:---------------------------|
| **1** | 🌐 **Open the app** | Three.js scene initializes; WebGL context created; MediaPipe model loads from CDN |
| **2** | 📷 **Enable camera** | `getUserMedia()` opens video stream; MediaPipe begins processing frames |
| **3** | ✊ **Close your fist** | Landmark curl-check fires; `isFist = true`; charge accumulator starts ticking |
| **4** | 🔥 **Fireball charges** | All six flame mesh layers scale up; particle emission rate increases; hum audio pitch rises |
| **5** | ⏱️ **Hold the charge** | `chargeLevel` accumulates each frame; fireball swells, flickers, and throws sparks |
| **6** | 🖐️ **Open your hand** | `isFist = false`; blast event fires; explosion geometry spawns; screen flash + shake triggers |
| **7** | 💥 **Explosion resolves** | Shockwave rings expand and fade; smoke drifts; debris decays; scene resets to idle |

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     CORE MECHANICS                            -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## ⚙️ Core Mechanics

### 🖐️ Hand Landmark Tracking

MediaPipe Hands outputs **21 3D landmarks** per detected hand, numbered 0 (wrist) through 20 (pinky tip). Each landmark carries normalized `x`, `y`, `z` coordinates. The wrist landmark (index `0`) is mapped linearly from MediaPipe's normalized `[0, 1]` space into Three.js world coordinates to position the fireball anchor in 3D space relative to the camera viewport.

```
MediaPipe Landmark Map (simplified):
  0 = Wrist          5,6,7,8   = Index  finger (MCP→tip)
  1,2,3,4 = Thumb    9,10,11,12 = Middle finger
                     13,14,15,16 = Ring   finger
                     17,18,19,20 = Pinky  finger
```

### ✊ Fist Detection Algorithm

Finger "curl" is determined by comparing each fingertip landmark's `y` position to its corresponding MCP (knuckle) joint:

```javascript
// Pseudocode — actual implementation checks all four fingers
function isFistClosed(landmarks) {
  const fingers = [
    [8, 5],   // Index  tip vs MCP
    [12, 9],  // Middle tip vs MCP
    [16, 13], // Ring   tip vs MCP
    [20, 17], // Pinky  tip vs MCP
  ];
  return fingers.every(([tip, mcp]) =>
    landmarks[tip].y > landmarks[mcp].y  // tip below knuckle → curled
  );
}
```

When all four fingers are curled below their MCP joints, the gesture is classified as a **closed fist**.

### ⚡ Charge Accumulation

Every animation frame that `isFist === true`, a `chargeLevel` float increments by a fixed delta (capped at `1.0`). The fireball's scale, emission rate, hum frequency, and flicker amplitude are all driven by this single normalized value, ensuring every visual and audio parameter responds uniformly to the charge state.

### 💥 Blast Triggering Logic

The blast fires the moment the gesture transitions from `isFist = true` → `false`. A minimum charge threshold prevents accidental micro-blasts from brief fist flickers. Above the threshold, `chargeLevel` directly scales the explosion's shockwave radius, particle count, and audio gain — a full charge produces a dramatically larger detonation than a half-charge.

### 🌟 Particle Generation

On explosion, `N` particles (where `N ∝ chargeLevel`) are spawned at the fireball's world position with randomized spherical velocity vectors. Each particle carries its own `lifetime`, `velocity`, and `opacity` decay rate, updated each frame and removed from the scene when `lifetime ≤ 0`.

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                  VISUAL EFFECTS BREAKDOWN                     -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🎨 Visual Effects Breakdown

The fireball is not a single mesh — it is **ten composited layers** that create the illusion of a living, turbulent fire.

```
        ╔══════════════════════════════════════╗
        ║         FIREBALL LAYER STACK         ║
        ╠══════════════════════════════════════╣
        ║  10. Dynamic Point Light  (PointLight)║  ← Casts real shadows
        ║   9. Smoke Particles      (Sprites)   ║  ← Post-explosion drift
        ║   8. Explosion Shards     (Points)    ║  ← Radial debris burst
        ║   7. Sparks               (Points)    ║  ← Continuous ember jets
        ║   6. Flame Jets           (Cones)     ║  ← Directional fire tongues
        ║   5. Heat Ring            (Torus)     ║  ← Radial heat distortion halo
        ║   4. Outer Flame Layer    (Sphere)    ║  ← Wispy corona, high opacity
        ║   3. Mid Flame Layer      (Sphere)    ║  ← Orange body, medium opacity
        ║   2. Inner Flame Layer    (Sphere)    ║  ← Yellow-white hot core shell
        ║   1. Core Sphere          (Sphere)    ║  ← Solid white-hot nucleus
        ╚══════════════════════════════════════╝
```

| Layer | Mesh Type | Material | Animation |
|:------|:----------|:---------|:----------|
| **Core Sphere** | `SphereGeometry` | `MeshStandardMaterial` — white-hot | Subtle pulsing scale oscillation |
| **Inner Flame** | `SphereGeometry` | `MeshStandardMaterial` — yellow, emissive | Faster pulse, slight rotation |
| **Mid Flame** | `SphereGeometry` | `MeshStandardMaterial` — orange, transparent | Turbulent wobble via sine waves |
| **Outer Flame** | `SphereGeometry` | `MeshStandardMaterial` — deep orange, high transparency | Slow rotation on all axes |
| **Heat Ring** | `TorusGeometry` | `MeshBasicMaterial` — orange, wireframe | Perpendicular spin, scale breathes |
| **Flame Jets** | `ConeGeometry` ×6 | `MeshStandardMaterial` — red-orange | Positioned radially; flicker in/out |
| **Sparks** | `Points` (BufferGeometry) | `PointsMaterial` — bright yellow | Random velocity; gravity decay |
| **Explosion Particles** | `Points` (BufferGeometry) | `PointsMaterial` — orange/white | Radial burst velocity; fade on lifetime |
| **Smoke Particles** | `Sprite` array | `SpriteMaterial` — grey, transparent | Upward drift; slow opacity decay |
| **Dynamic Light** | `PointLight` | — | Intensity flickers with charge level |

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                      INSTALLATION                             -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🚀 Installation

No build step. No Node.js. No package manager. Just clone and open.

### Prerequisites

- A modern browser with **WebGL 2.0** support (Chrome 80+, Firefox 78+, Edge 88+, Safari 15+)
- A working **webcam or device camera**
- **HTTPS** or `localhost` (required for `getUserMedia` camera access)

### Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/fireball-xr.git

# 2. Navigate into the project
cd fireball-xr

# 3. Open directly in your browser
open index.html
# — OR — serve locally for camera access (recommended)
```

### Recommended: Local Server

Camera access (`getUserMedia`) requires a secure context. Use any of these zero-config options:

```bash
# Option A — Python (built-in, no install)
python3 -m http.server 8080
# → Open http://localhost:8080

# Option B — Node.js (npx, no global install)
npx serve .
# → Open http://localhost:3000

# Option C — VS Code
# Install the "Live Server" extension → Right-click index.html → "Open with Live Server"
```

> 💡 **Tip:** For the best experience, use **Google Chrome** on a desktop or laptop with good ambient lighting.

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                         USAGE                                 -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📖 Usage

### First Launch

1. **Open the app** in your browser via `localhost` or an HTTPS URL
2. **Click "Allow"** when the browser requests camera permission
3. **Position your hand** in the center of the frame, palm facing the camera
4. Wait for the green tracking indicator — MediaPipe has locked on to your hand

### Casting a Fireball

| Action | Gesture | Effect |
|:-------|:--------|:-------|
| **Idle** | ✋ Open hand, relaxed | Camera feed visible; no fireball |
| **Ignite** | ✊ Slowly close your fist | Fireball spawns at your knuckles |
| **Charge** | ✊ Hold the fist steady | Fireball grows, brightens, sparks fly |
| **Full Power** | ✊ Hold for 2–3 seconds | Fireball reaches maximum size; screen glows |
| **Detonate** | ✋ Snap hand open | 💥 Explosion! Shockwave, smoke, debris |
| **Recharge** | ✊ Close fist again | New fireball ignites immediately |

### Tips for Best Results

- 🌟 **Lighting matters** — ensure your hand is well-lit from the front
- 🖐️ **Face your palm** toward the camera for the most accurate landmark detection
- ↔️ **Keep your hand** within the center 60% of the frame
- 🐢 **Slow down** your open/close gesture — rapid flickers can confuse the detector
- 🔊 **Enable audio** — the sound design is half the experience

### Debug Panel

Press **`D`** to toggle the real-time debug overlay, which shows:
- Current gesture state (`IDLE` / `CHARGING` / `EXPLODING`)
- `chargeLevel` percentage
- MediaPipe landmark coordinates (wrist, index tip, pinky tip)
- Renderer FPS counter
- Active particle count

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                  PERFORMANCE OPTIMIZATIONS                    -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## ⚡ Performance Optimizations

Fireball XR is engineered to maintain **60 fps** even on mid-range hardware:

| Optimization | Implementation |
|:-------------|:---------------|
| **`requestAnimationFrame` loop** | All rendering and physics tied to `rAF` — never runs faster than the display refresh rate, never wastes CPU when the tab is hidden |
| **WebGL / GPU rendering** | Three.js delegates all draw calls to the GPU via WebGL 2.0 — thousands of particles computed in parallel on the graphics card |
| **BufferGeometry for particles** | Spark and explosion particles use `Float32Array`-backed `BufferGeometry` instead of individual `Mesh` objects — a single draw call renders all points |
| **Particle pooling** | Dead particles are reset and reused rather than garbage-collected — eliminates GC pauses during heavy explosions |
| **Frustum culling** | Three.js automatically skips rendering objects outside the camera frustum |
| **MediaPipe WASM** | Hand detection runs on a compiled WebAssembly module — near-native speed with no server round-trips |
| **Texture atlasing** | Smoke sprites share a single texture atlas to minimize GPU state changes |
| **Conditional audio** | Web Audio nodes are created on first interaction and reused — `AudioContext` is never re-instantiated per explosion |

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    PROJECT STRUCTURE                          -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📁 Project Structure

```
fireball-xr/
│
├── 📄 index.html              # App entry point — loads all scripts & styles
├── 📄 README.md               # You are here
├── 📄 LICENSE                 # MIT License
│
├── 📂 css/
│   └── 🎨 style.css           # Dark-theme UI, overlay HUD, canvas positioning
│
├── 📂 js/
│   ├── 🔥 fireball.js         # Core fireball state machine & charge logic
│   ├── 👁️  handTracker.js      # MediaPipe Hands integration & landmark parsing
│   ├── 🌟 particles.js        # Spark, explosion, and smoke particle systems
│   ├── 🎭 effects.js          # Shockwave rings, screen flash, camera shake
│   ├── 🔊 audio.js            # Web Audio API — crackle, hum, and boom synth
│   ├── 🖥️  renderer.js         # Three.js scene, camera, lights, rAF loop
│   └── 🐛 debug.js            # Debug overlay panel and FPS counter
│
├── 📂 assets/
│   ├── 📂 textures/
│   │   ├── 🖼️  smoke-sprite.png  # Smoke particle sprite atlas
│   │   └── 🖼️  spark.png         # Spark glow texture
│   └── 📂 screenshots/
│       ├── 🖼️  demo-idle.png
│       ├── 🖼️  demo-charging.png
│       └── 🖼️  demo-explosion.png
│
└── 📄 .github/
    ├── 📂 ISSUE_TEMPLATE/
    │   ├── bug_report.md
    │   └── feature_request.md
    └── 📄 CONTRIBUTING.md
```

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                   FUTURE ENHANCEMENTS                         -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🚀 Future Enhancements

> _The spellbook isn't finished yet._

| Enhancement | Description | Priority |
|:------------|:------------|:--------:|
| 🌊 **Water Blast** | Left-hand gesture spawns a water-wave projectile using fluid shader | 🔴 High |
| ⚡ **Lightning Strike** | Two-hand gesture (both index fingers pointed) triggers forked lightning | 🔴 High |
| 🌀 **Gesture Library** | Expandable gesture → spell mapping system; plug in new spells via JSON config | 🟡 Medium |
| 👥 **Multiplayer Battle Mode** | WebRTC peer-to-peer: two players cast spells at each other over a data channel | 🟡 Medium |
| 🎙️ **Voice Commands** | Web Speech API: say "EXPECTO" to hold charge, "PATRONUM" to release | 🟡 Medium |
| 📱 **Mobile AR Support** | WebXR Device API: overlay spells on your real environment via phone camera | 🟠 Planned |
| 🤖 **AI Spell Generation** | Prompt an LLM to describe a new spell; procedurally generate its particle parameters | 🟠 Planned |
| 🏆 **Achievement System** | Track combo chains, charge durations, and explosion counts with localStorage badges | 🟢 Backlog |
| 🌐 **Internationalization** | i18n support for UI labels and debug panel | 🟢 Backlog |
| 🎮 **Gamepad Support** | Fallback controller input for users without camera access | 🟢 Backlog |

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                      SCREENSHOTS                              -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📸 Screenshots

<div align="center">

| Idle State | Charging | Full Explosion |
|:----------:|:--------:|:--------------:|
| ![Idle](assets/screenshots/demo-idle.png) | ![Charging](assets/screenshots/demo-charging.png) | ![Explosion](assets/screenshots/demo-explosion.png) |
| _Open hand — no fireball_ | _Fist closed — growing charge_ | _Hand opened — detonation!_ |

> 🖼️ _Screenshots coming soon — [contribute yours!](#-contributing)_

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                   BROWSER COMPATIBILITY                       -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🌐 Browser Compatibility

| Browser | Version | Status |
|:--------|:--------|:------:|
| ![Chrome](https://img.shields.io/badge/Chrome-80+-4285F4?style=flat-square&logo=googlechrome&logoColor=white) | 80+ | ✅ Full support |
| ![Firefox](https://img.shields.io/badge/Firefox-78+-FF7139?style=flat-square&logo=firefox&logoColor=white) | 78+ | ✅ Full support |
| ![Edge](https://img.shields.io/badge/Edge-88+-0078D7?style=flat-square&logo=microsoftedge&logoColor=white) | 88+ | ✅ Full support |
| ![Safari](https://img.shields.io/badge/Safari-15+-000000?style=flat-square&logo=safari&logoColor=white) | 15+ | ⚠️ Requires HTTPS |
| ![Mobile Chrome](https://img.shields.io/badge/Mobile%20Chrome-80+-4285F4?style=flat-square&logo=googlechrome&logoColor=white) | 80+ | ✅ Supported |
| ![Mobile Safari](https://img.shields.io/badge/Mobile%20Safari-15+-000000?style=flat-square&logo=safari&logoColor=white) | 15+ | ⚠️ Limited WebGL |

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                      CONTRIBUTING                             -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. **Any contribution you make is greatly appreciated.**

### How to Contribute

```bash
# 1. Fork the repository
# Click "Fork" on GitHub → creates your own copy

# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/fireball-xr.git
cd fireball-xr

# 3. Create a feature branch
git checkout -b feature/my-awesome-spell

# 4. Make your changes & commit
git add .
git commit -m "feat: add ice shard spell with freeze effect"

# 5. Push to your fork
git push origin feature/my-awesome-spell

# 6. Open a Pull Request on GitHub
```

### Contribution Guidelines

- 🐛 **Bug reports** — Use the [Bug Report template](.github/ISSUE_TEMPLATE/bug_report.md) with steps to reproduce
- ✨ **Feature requests** — Open a [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md) to discuss before implementing
- 📖 **Documentation** — Typos, clarifications, and improvements always welcome
- 🎨 **New spells** — Add them in `js/fireball.js` following the existing spell interface
- 🧪 **Tests** — Manual test on Chrome + Firefox before submitting a PR

### Code Style

- Use `camelCase` for variables and functions
- Comment all Three.js geometry parameters
- Keep each file focused on a single responsibility
- No external dependencies beyond Three.js and MediaPipe

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    STAR ENCOURAGEMENT                         -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## ⭐ Show Your Support

<div align="center">

**If Fireball XR made you feel like a wizard, consider giving it a star!**

[![GitHub Star](https://img.shields.io/github/stars/yourusername/fireball-xr?style=for-the-badge&logo=github&color=FFD700&labelColor=000000)](https://github.com/yourusername/fireball-xr/stargazers)

_Stars help the project gain visibility and motivate future development._
_It takes 2 seconds and means the world. 🙏_

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                        LICENSE                                -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📜 License

Distributed under the **MIT License** — free to use, modify, and distribute with attribution.

See [`LICENSE`](LICENSE) for full text.

```
MIT License — Copyright (c) 2024 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                         AUTHOR                                -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 👤 Author

<div align="center">

<img src="https://github.com/yourusername.png" width="100" style="border-radius: 50%;" />

### **Your Name**
_Full-Stack Developer · Creative Technologist · WebGL Wizard_

[![GitHub](https://img.shields.io/badge/GitHub-yourusername-181717?style=for-the-badge&logo=github)](https://github.com/yourusername)
[![Twitter](https://img.shields.io/badge/Twitter-@yourhandle-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/yourhandle)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-yourname-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourname)
[![Portfolio](https://img.shields.io/badge/Portfolio-yoursite.dev-FF6B35?style=for-the-badge&logo=firefox&logoColor=white)](https://yoursite.dev)

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    ACKNOWLEDGEMENTS                           -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🙌 Acknowledgements

- [**MediaPipe**](https://mediapipe.dev/) by Google — for the incredibly accurate real-time hand tracking model
- [**Three.js**](https://threejs.org/) — for the beautiful, accessible WebGL abstraction layer
- [**shields.io**](https://shields.io/) — for the badge infrastructure
- [**capsule-render**](https://github.com/kyechan99/capsule-render) — for the animated header banner
- The open-source WebXR community for pushing the boundaries of what browsers can do

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     SEO KEYWORDS                              -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<!-- 
  Keywords: hand tracking javascript, mediapipe hands browser, three.js fireball effect,
  webgl particle system, gesture recognition web, real-time hand detection, 
  web audio api sound effects, camera gesture control, javascript magic effects,
  threejs explosion particles, browser ar hand tracking, open hand fist detection,
  webgl fire simulation, mediapipe javascript tutorial, gesture controlled web app
-->

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%" />

**Built with ❤️ and JavaScript**

_"Any sufficiently advanced technology is indistinguishable from magic."_
_— Arthur C. Clarke_

<br />

[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/yourusername/fireball-xr)
[![Powered by WebGL](https://img.shields.io/badge/Powered%20by-WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)](https://www.khronos.org/webgl/)
[![Open Source](https://img.shields.io/badge/Open-Source-4CAF50?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](https://opensource.org/)

<br />

© 2024 Your Name · [MIT License](LICENSE) · [Report Bug](https://github.com/yourusername/fireball-xr/issues) · [Request Feature](https://github.com/yourusername/fireball-xr/issues)

</div>
