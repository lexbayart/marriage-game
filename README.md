<div align="center">

# 👩‍❤️‍👨 My Best Wife
### A marriage survival game

[![Play Online](https://img.shields.io/badge/▶_PLAY_NOW-GitHub_Pages-brightgreen?style=for-the-badge)](https://lexbayart.github.io/marriage-game/)
[![Version](https://img.shields.io/badge/version-9.0.4-blue?style=for-the-badge)](./index.html)
[![Status](https://img.shields.io/badge/status-beta-orange?style=for-the-badge)](#-development-status)

**[▶ Open in browser — try it now](https://lexbayart.github.io/marriage-game/)**
No install. No account. Works offline.

[![Gameplay](https://github.com/lexbayart/marriage-game/raw/master/images/Застявка.gif)](https://lexbayart.github.io/marriage-game/)

</div>

---

## ⚠️ A note before you play

This game is built in the **survival** genre — and it is deliberately hard.

It is not intended to offend anyone. The author's goal was to explore the real pressures of marriage through game mechanics, the same way other survival games explore starvation, war, or natural disaster. If something in this game makes you uncomfortable, that reaction is probably the point.

---

## 💡 Why this game exists

The author loves survival games — the kind where you keep coming back to something impossibly difficult. At some point, he asked himself: **what is the hardest thing people still voluntarily choose, over and over again?**

Marriage.

And within marriage — being the **wife**.

The author's observation is that society places the heaviest burden of a marriage's success or failure on the woman. She is more often blamed when it falls apart. The emotional labor, the children, the household — these land disproportionately on her. Meanwhile, the husband is often perceived as someone who simply lives his life.

So in this game, **you play as the wife.** The husband is an NPC — an autonomous character driven entirely by his own goals. He doesn't fight for the marriage. He doesn't compromise. He wanders, works, rests on the couch. You cannot control him directly. You can only influence him — through tools that look a lot like the real ones: affection, tears, beauty, timing.

Whether the marriage survives or ends is entirely in your hands. And the game makes sure you feel the weight of that.

---

## 🎮 Core mechanics

You are the wife (👩) on a top-down canvas world. The husband (👨) roams autonomously, driven by his own logic.

**The central rule:** The wife must stay within the husband's radius. Stray too far for too long — and it's over. He is your safe zone. He is also your main challenge.

### Tools of influence

| Action | What it does |
|--------|-------------|
| 💋 **Kiss** | Directs the husband toward a destination. Loses effectiveness if overused |
| 😢 **Cry** | Draws him to you. A manipulation — but it works |
| 💬 **Talk** | Reduces intrusive thoughts, may reveal his hidden interests |
| 🛋️ **Couch** | A trap. Once he's on it, he's immobile for 40 seconds |

### Resources

| Item | Effect |
|------|--------|
| 🪙 Coins | Husband earns them — his radius grows |
| 🍫 Chocolate | Speed buff for wife, helps during pregnancy |
| 💄 Lipstick | Strengthens the kiss, can wake him from the couch |
| 👗 Dress | Prevents accidental pregnancy, boosts beauty |
| 💍 Ring | Extends your time outside his radius, increases pregnancy chance |

### The full lifecycle

The game simulates an **entire life**:
- Pregnancy, birth, children orbiting the wife, growing up and leaving home
- Divorce is not a game over — a remarriage screen appears with new candidates
- The game continues until the wife dies at a randomly determined age

---

## 🌍 A social experiment

The author began sharing the game with people he knew — and noticed a pattern:

> Women who had ended multiple relationships tended to react with anger: the game felt unfair, the mechanics felt punishing.
>
> Men, regardless of relationship history, genuinely tried to survive. They gave gameplay advice. They admitted it was very hard.

The reaction to the game became as interesting as the game itself. How you feel about the mechanics says something about how you feel about marriage.

---

## 📊 Real statistics inside the game

The remarriage probability system is based on **real demographic data**:

- Chances decrease with age
- Each child reduces them further
- A second divorce lowers them again

These numbers were deliberately softened for playability — but not by much. The goal is to show players an honest picture of what remarriage actually looks like statistically, not to demoralize.

---

## ♑️ Husband archetypes — zodiac system *(work in progress)*

One of the planned systems for replayability: **zodiac signs as husband archetypes**. Each sign would give the husband unique behaviors, passive traits, and weaknesses — making every run feel different.

### What's implemented
- **♑️ Capricorn** — the only fully built archetype (35% chance per husband)
  - Does not get tired after work
  - Driven by career ambition (level 10+ unlocks "Boss" status)
  - Has a rotating **Ice Blade** mechanic that attacks enemies

### What's planned but not built
The remaining 11 signs — ♒ ♓ ♈ ♉ ♊ ♋ ♌ ♍ ♎ ♏ ♐ — each with their own behavioral logic.

This is where development paused. Adding Capricorn alone was a significant undertaking. Completing the system requires more hands than one person has.

---

## ✨ What's currently in the game

- 💍 Ring-based marriage system — two inversely linked health bars
- 👨 Procedural husband generation — random emoji, age, skin tone, career level, previous husbands avoided
- 💼 Career progression — 22 job titles from "Slipper Observer" to "The One Who Hides Behind Deputies"
- 👶 Full family simulation — pregnancy, birth, children who orbit, grow, and eventually leave
- 🏠 House decoration — 9×9 grid, furniture catalog, budget tracking
- 🎰 Casino & alcohol — unlock over time, affect husband behavior
- ⚖️ Judge encounters — unpaid bills summon a boss fight
- 🐱 Cat system — tame cats, manage their population, watch them age
- 📊 Session statistics — track every husband, career, children, and remarriage across playthroughs
- 📖 Built-in tutorial

---

## 🚧 Development status

The game is **playable and complete enough to experience the core concept** — but unfinished.

### Known gaps
- Zodiac archetype system: only Capricorn exists (1 of 12)
- No mobile/touch controls
- No sound design
- The husband's hidden interests system, the "US" relationship parameter, and furniture effects are partially designed but not fully implemented
- Adding new features has a history of breaking existing ones — the codebase needs architectural attention

### Why development paused

Each new mechanic added to the single HTML file created regressions in what was already working. The scope of what's designed is larger than one developer can maintain alone.

---

## 🤝 Looking for collaborators

If you find the concept interesting and want to contribute:

- 🎮 **Game designers** — especially those with experience in replayability systems, archetype design, and difficulty balancing
- 🧠 **Developers** — comfortable working inside a large vanilla JS/HTML5 canvas codebase
- 🧪 **Playtesters** — willing to give honest, detailed feedback

Open an [Issue](../../issues) or start a [Discussion](../../discussions). The design documentation is included in this repo.

---

## 🚀 Run it

**[▶ lexbayart.github.io/marriage-game](https://lexbayart.github.io/marriage-game/)**

Or clone and open locally — fully standalone, no build step:

```bash
git clone https://github.com/lexbayart/marriage-game.git
open marriage-game/index.html
```

---

## 📖 Documentation

- [**Complete User Guide**](./docs/GUIDE.md) — all mechanics, hotkeys, unlock progression

---

## 🗂️ Repository structure

```
marriage-game/
├── index.html              # The entire game — one file
├── docs/
│   └── GUIDE.md            # Complete player guide
├── images/
│   └── Застявка.gif        # Gameplay preview
└── README.md               # This file
```

---

## 🛠️ Tech

Vanilla JS · HTML5 Canvas · Web Audio API · Emoji rendering  
Single HTML file · Zero dependencies · Zero build step

---

## 💬 Contact

- **Telegram:** [@lexbayart](https://t.me/lexbayart)
- **GitHub Issues:** [Open an issue](../../issues)

---

## 📄 License

© 2025 lexbayart — [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)  
Free to use and share for non-commercial purposes with credit.

---

<div align="center">

*The game is hard. Marriage is too. That's not a bug.*

</div>
