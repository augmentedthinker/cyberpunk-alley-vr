# Neo-Tokyo Noodle Hearth 🏮 (Meta Quest 2 WebXR)

> **Live WebXR Experience**: [https://augmentedthinker.github.io/cyberpunk-alley-vr/](https://augmentedthinker.github.io/cyberpunk-alley-vr/)  
> **Synthesized**: September 25, 2026 • Horizon Sanctuary (Christopher & Antigravity)  
> **Target Hardware**: Meta Quest 2 Browser (WebXR 6DoF) & Desktop WebGL  

An atmospheric, explorable 3D virtual environment generated from a single 2D concept image via **Hugging Face ZeroGPU** using Tencent's **WorldMirror 2.0** universal geometric foundation model.

---

## 🎮 Controls & Exploration

### Meta Quest 2 (WebXR Mode)
1. Open this page in the **Meta Quest Browser**.
2. Click the cyan **"ENTER VR"** button at the bottom of the screen.
3. Put on your headset:
   - **Left Thumbstick**: Smooth gliding locomotion (forward, backward, strafe side-to-side relative to head gaze).
   - **Right Thumbstick**: Astra Comfort Snap-Turning (30° incremental yaw rotation).
   - **6DoF Head Tracking**: Naturally crouch, tilt, or lean to inspect puddle reflections and wall neon tubes with real-time motion parallax.

### Desktop Browser (WebGL Mode)
- **W / A / S / D** or **Arrow Keys**: Walk through the alleyway.
- **Mouse Click & Drag**: Look around the scene.
- **Hotspot Buttons**: Quick-teleport to Entrance, Noodle Counter, Neon Wall, or Deep Alley.
- **Audio Button**: Toggle procedural Web Audio ambient rain & 60Hz electrical transformer hum.

---

## 🔬 Architectural Innovations

1. **The Spatial 90/10 Fallacy Solved**:
   - Rather than burning cloud compute on single isolated props that look detached in empty space, this workflow uses a single ~25-second ZeroGPU burst to generate an entire explorable *place*.
2. **Flush-Mounted Signage Breakthrough**:
   - In single-view 3D neural reconstruction, blade signs jutting out into the street leave hollow backside gaps. By designing the conditioning plate with all neon tubes and fascia boards mounted flush against the building walls, the sign's back is the wall itself—yielding solid, continuous 3D geometry without paper-thin artifacts.
3. **Hardware Budget Discipline**:
   - Extracted mesh: **236,894 triangles** (4.61 MB GLB).
   - Custom self-illuminated double-sided vertex-color shaders prevent dark lighting washouts and sustain rock-solid 72/90 FPS on Qualcomm Snapdragon XR2 Gen 1 hardware.
