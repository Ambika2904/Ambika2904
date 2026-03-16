# ZARVEN — Level 2: Mass Matters
### Gamified Periodic Table Learning Platform

A browser-based educational snake game for learning the periodic table.
Built as part of the ZARVEN independent study project.

---

## How to Host on GitHub Pages (Free Shareable Link)

### Step 1 — Create a GitHub Account
- Go to https://github.com and sign up (free)

### Step 2 — Create a New Repository
1. Click the **+** button (top right) → **New repository**
2. Repository name: `zarven-game` (or any name you like)
3. Set to **Public**
4. Click **Create repository**

### Step 3 — Upload the Files
1. In your new repository, click **Add file → Upload files**
2. Upload ALL four files:
   - `index.html`
   - `style.css`
   - `elements.js`
   - `game.js`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository **Settings** tab
2. Scroll down to **Pages** (in the left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: select `main`, folder: `/ (root)`
5. Click **Save**

### Step 5 — Get Your Shareable Link
- Wait about 1–2 minutes
- Your game will be live at:
  `https://YOUR-USERNAME.github.io/zarven-game/`
- Share this link with anyone — no login needed to play!

---

## Game Features

### Two Modes
| Mode | Player 1 | Player 2 |
|------|----------|----------|
| Human vs Robot | W A S D keys | Robot AI (automatic) |
| Human vs Human | W A S D keys | Arrow keys |

### Element Ranges
- **Z 1–10** — Hydrogen to Neon (beginner)
- **Z 11–20** — Sodium to Calcium (intermediate)
- **Z 1–20** — All 20 elements (full range)

### How to Score
- **Eat elements** → grow snake + score atomic mass points
- **Heavier element** = bigger circle on screen = more points + more growth
- **Noble gases** (dashed circle) → eating one freezes your snake for 2 seconds
- **90-second timer** — most points wins!
- **3 lives** each — respawn on wall/self collision

### Real-World Examples
Every element eaten shows its real-world use (e.g. Carbon → "Diamonds, life itself").
This is the core educational mechanic from the ZARVEN platform design.

---

## File Structure

```
zarven-game/
├── index.html     ← Page structure and screens (menu, game, results)
├── style.css      ← All visual styling (dark sci-fi theme)
├── elements.js    ← Periodic table data (Z1–20) with examples
└── game.js        ← All game logic: snake movement, robot AI, drawing
```

---

## Academic Context

This prototype implements **Level 2: Mass Matters** of the ZARVEN gamified
learning platform, as described in the Week 7 design specification:

- Single player and 2-player modes
- Element range selection (prerequisite progression)
- Heavy elements score more (atomic mass mechanic)
- Noble gas penalty mechanic
- Real-world element examples (educational HUD)

Built for: Independent Study — Designing a Data-Driven Gamified Digital
Platform to Improve Conceptual Understanding of the Periodic Table.
