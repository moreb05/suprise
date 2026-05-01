# 💕 Hey Chama, Are You Coming Back?

A romantic animated surprise page built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies. Three hand-crafted scenes that play out as you scroll.

---

## ✨ What's Inside

### 🚗 Scene 1 — The Journey
A car animates along a dotted road from **Kitwe** all the way to **Lusaka**, with a starry night sky in the background. When it arrives, the message *"arriving straight to my arms"* fades in.

### 🐻🐻 Scene 2 — Already Us
Two bears dance to floating music notes with a love heart between them — labelled *"us when you finally get here 🥰"*.

### 💗 Scene 3 — Confetti & Love
An infinite confetti explosion rains down over a glowing **"hey chama, when are you coming?"** message, a personal love note, and a row of hand-drawn animated daisies.

---

## 🗂️ Project Structure

```
v-day/
├── surprise.html    # The full animated surprise — all scenes in one file
└── README.md
```

---

## 🚀 Running It

No build step needed. Just open `surprise.html` in any browser:

```bash
# Option 1 — double-click surprise.html in File Explorer

# Option 2 — open from terminal
start surprise.html
```

Or deploy to **GitHub Pages**:
1. Go to your repo → **Settings** → **Pages**
2. Source: **Deploy from a branch** → `main` → `/ (root)` → **Save**
3. Your page goes live at `https://yourusername.github.io/v-day/surprise.html` in ~2 minutes

---

## 🛠️ Customising

All content lives in `surprise.html`. Key spots to edit:

| What | Where to look |
|---|---|
| City labels (Kitwe / Lusaka) | `.road-label` `<span>` tags in Scene 1 |
| Arrival message | `.arrive-msg` div in Scene 1 |
| Bears label | `.bears-label` div in Scene 2 |
| "Hey chama" text | `.hey-chama-confetti` div in Scene 3 |
| Love message | `.love-msg` div in Scene 3 |
| Number of daisies | `heights` array in the daisies JS block |
| Confetti colours | `colors` array in the confetti JS block |

---

## License

Do whatever you want with it. Make someone smile. 💕
