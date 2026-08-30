<div align="center">

  <h1>MotionVector</h1>
  <p><strong>Autonomous Agentic Video Studio & AI Compute Fleet Systems</strong></p>

  <p>
    <a href="https://motionvector.dev"><img src="https://img.shields.io/badge/Platform-motionvector.dev-000000?style=flat-square" alt="Platform" /></a>
    <a href="https://spacepilot.ai"><img src="https://img.shields.io/badge/SpacePilot-Provenance--First-c9a227?style=flat-square" alt="SpacePilot" /></a>
    <img src="https://img.shields.io/badge/Engine-48%20FPS%20%C2%B7%20DocIR%20Sealed-18181b?style=flat-square" alt="DocIR Engine" />
  </p>

</div>

---

### 📼 The Playhead Law

> *"The playhead sweeps once and the document renders behind it, at constant speed, because a render has no easing. Then the patch lands: five frames re-render, one at a time, and nothing else moves."*

```text
  ┌──┐┌──┐┌──┐                               ┌──┐┌──┐┌──┐
  │  ││  ││  │                               │  ││  ││  │
  │  ││  ││  │ ┌──┐                     ┌──┐ │  ││  ││  │
  │  ││  ││  │ │  │ ┌──┐           ┌──┐ │  │ │  ││  ││  │
  │  ││  ││  │ │  │ │  │ ┌──┐ ┌──┐ │  │ │  │ │  ││  ││  │       ┌──┐                ┌──┐
  │  ││  ││  │ │  │ │  │ │  │ │  │ │  │ │  │ │  ││  ││  │  │    │  │ ┌──┐      ┌──┐ │  │
  │  ││  ││  │ │  │ │  │ │  │ │  │ │  │ │  │ │  ││  ││  │  │    │  │ │  │ ┌──┐ │  │ │  │
  └──┘└──┘└──┘ └──┘ └──┘ └──┘ └──┘ └──┘ └──┘ └──┘└──┘└──┘  ▼    └──┘ └──┘ └──┘ └──┘ └──┘
   [0] [1] [2]  [3]  [4]  [5]  [6]  [7]  [8]  [9][10]    │    [0]  [1]  [2]  [3]  [4]
   ◄───────────────  M (11-SLAT RENDER)  ───────────────► │    ◄──  v (5-FRAME PATCH)  ──►
                                                          PLAYHEAD (SEEK: 0.00s ──> 4.80s)
```

---

### 🚀 Core Platform & Runtime

```
┌─────────────────────────────────────┬────────────────────────────────────────────────────────────────────────┐
│ System                              │ Status & Quickstart                                                    │
├─────────────────────────────────────┼────────────────────────────────────────────────────────────────────────┤
│ MotionVector Runtime Engine         │ $ npx mvec                                                             │
│                                     │ Deterministic DocIR video rendering through sealed MCP domain verbs    │
├─────────────────────────────────────┼────────────────────────────────────────────────────────────────────────┤
│ MotionVector Studio                 │ Coming soon at studio.motionvector.dev                                 │
│                                     │ ↳ Join waitlist on https://motionvector.dev                            │
├─────────────────────────────────────┼────────────────────────────────────────────────────────────────────────┤
│ SpacePilot                          │ Coming soon: pip install spacepilot                                    │
│                                     │ Provenance-first decision layer for single-owner AI compute fleets     │
├─────────────────────────────────────┼────────────────────────────────────────────────────────────────────────┤
│ SpacePilot MacBar App               │ Coming soon: SpaceBar.app                                              │
│                                     │ Native macOS menu bar status monitor & fleet placement HUD             │
└─────────────────────────────────────┴────────────────────────────────────────────────────────────────────────┘
```

---

### 🧪 Open Source Tooling

```
┌───────────────────────────┬────────────────────────────────────────────────────────────────────────┐
│ Project                   │ Description & Direct Links                                             │
├───────────────────────────┼────────────────────────────────────────────────────────────────────────┤
│ AgentWorth                │ $ npx agwt  (alias: npx agentworth)                                    │
│                           │ Trajectory discovery & token receipts for high-performing agentic devs │
│                           │ ↳ Web: https://agentworth.dev                                          │
│                           │ ↳ Source: https://github.com/unfoundbox/agentworth                     │
├───────────────────────────┼────────────────────────────────────────────────────────────────────────┤
│ WebCodecs Census          │ Zero-overhead allocator telemetry & leak audits for WebCodecs/MediaBunny│
│                           │ ↳ Package: npm install @motionvector/webcodecs-census                  │
│                           │ ↳ Documentation: https://motionvector-dev.github.io/webcodecs-census/ │
└───────────────────────────┴────────────────────────────────────────────────────────────────────────┘
```

---

### 🔬 In Lab

* **ACI (Agent Computer Interface)** — Upcoming latent space paper.

---

<div align="center">
  <sub>Engineered with precision by MotionVector · <a href="https://motionvector.dev">motionvector.dev</a></sub>
</div>
