# 🔥 SaiyanVelocity — Zero-API Power Level & Focus-Lift Tracker

> **Deterministic Client-Side Dragon Ball Power Engine for Deep Work & Athletic Training**  
> *Zero external API keys • Zero rate limits • 100% Client-Side LocalStorage Persistence*

Built by **[Ammar Akhund](https://xakhundx.github.io/Portfolio/)** (Economics Major & Statistics Minor, University of Manitoba `'27`).

---

## 🎯 Executive Overview & Purpose

**SaiyanVelocity** represents the direct architectural evolution of my earlier Dragon Ball Pomodoro focus app.

In the original prototype, generating AI study insights required users to input a manual Google Gemini API key. This introduced three critical real-world problems:
1. **User Friction:** Non-technical visitors don't want to create an AI Studio account or manage API quotas.
2. **Key Exposure Risks:** Client-side keys in browser memory trigger security alerts on GitHub.
3. **Flaky Network Dependency:** When the API is throttled or offline, the app breaks.

**SaiyanVelocity replaces external LLM API dependency with a deterministic client-side mathematical progression engine.** It treats cognitive focus and athletic training as an integrated power system inspired by Akira Toriyama's Dragon Ball universe.

---

## 🔬 Deterministic Power Math Engine

- **Base Saiyan Power Threshold:** $9,000$ (*"It's over 9,000!"*)
- **Weekly Focus Multiplier ($M_{\text{focus}}$):**
  $$M_{\text{focus}} = 1 + \left(\frac{\text{Weekly Focus Hours}}{15}\right)$$
- **Physical Training Volume Multiplier ($M_{\text{gym}}$):**
  $$M_{\text{gym}} = 1 + (\text{Workout Days} \times 0.15) + (\text{Total Sets} \times 0.005)$$
- **Zenkai Consistency Streak Boost ($M_{\text{zenkai}}$):**
  $$M_{\text{zenkai}} = 1.04^{\text{Streak Days}}$$
- **Final Power Level Formulation:**
  $$\text{Power Level} = 9000 \times M_{\text{focus}} \times M_{\text{gym}} \times M_{\text{zenkai}}$$

### Transformation Tiers
- **Base Saiyan:** $9,000 – 25,000$ (0–10 Focus hrs/wk)
- **Kaio-Ken (x10):** $25,000 – 100,000$ (10–25 Focus hrs/wk + 2 workouts)
- **Super Saiyan 1 (Golden Ki):** $100,000 – 500,000$ (25–40 Focus hrs/wk + 4 workouts)
- **Super Saiyan 3 (Ascended):** $500,000 – 1,500,000$ (40–55 Focus hrs/wk + 5 workouts)
- **Ultra Instinct (Autonomous):** $1,500,000+$ (55+ Focus hrs/wk + flawless discipline streak)

---

## 🛠️ Architecture & Tech Stack

- **Zero-API Pomodoro Engine:** Integrated focus timer (25 min, 50 min, 5 min break) with native **Web Audio API offline synthesizer** chimes.
- **Dynamic HTML5 Canvas Particle Aura:** GPU-accelerated Ki aura field with pulsating radial gradients and upward sparks.
- **Data Visualization:** Dual-axis **Chart.js (v4.4)** plotting Daily Focus Hours vs. Compounded Power Level Trajectory.
- **Storage:** Instant browser `localStorage` synchronization with JSON export.
- **Social Engine:** 1-Click **LinkedIn Transformation Post Generator** explaining the software engineering philosophy of deterministic math over API reliance.

---

## 🚀 Running Locally or Deploying to GitHub Pages

### Run Locally
Open `index.html` directly in any web browser.

### Deploy to GitHub Pages
```bash
git init
git add .
git commit -m "feat: initial release of SaiyanVelocity zero-api focus engine"
git branch -M main
git remote add origin https://github.com/xakhundx/saiyan-velocity.git
git push -u origin main
```
Then navigate to **Repository Settings → Pages → Deploy from branch (main)**.
