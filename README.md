# ⚔️ Dhurandhar Contest Dashboard

Live, mobile-first contest leaderboard for the **Q1 FY26-27 Dhurandhar Sales Contest** at Honasa Consumer — tracking **24 ASMs across 8 zones** on **ME Face Wash | Sun** and the **Emerging Brand portfolio**.

🔗 **Live**: [sonusaifi-mamearth.github.io/Dhurandhar](https://sonusaifi-mamearth.github.io/Dhurandhar/)

---

## 📊 What It Shows

| Section | What's Inside |
| --- | --- |
| **Hero + Scoreboard** | Two big KPI cards — ME FW & Emerging Brand QTD, target, Ach%, BTG |
| **Ticker** | Rolling highlights — zone toppers, breakout ASMs, war-room flags |
| **Zone Slicer** | One-tap filter across NORTH-1/2, CENTRAL, WEST-1/2, SOUTH-1/2, EAST |
| **Battlefield Tables** | Full Region × ASM grid — QTR Tgt · Apr · May · Jun · QTD · Ach% · BTG, with zone subtotals + grand total |
| **🏆 Champions In Action** | Top 6 ASMs ≥ 85% achievement per brand |
| **🚨 Need Acceleration** | Bottom 6 ASMs < 45% — war-room focus |
| **🏁 Race To Finish** | Animated zone-level ranking bars |

---

## 🛠️ Tech

- **100% static** — single `index.html`, no build step, no dependencies
- **Fonts**: Oswald (display) + Barlow (body) via Google Fonts
- **Data**: inlined as JS arrays at the bottom of `index.html`
- **Hosting**: GitHub Pages (default branch)
- **Distribution**: GitHub Pages URL → Bitly shortlink → WhatsApp broadcast to ASM/RSM/ZSM groups

---

> **Tip**: Zone subtotals and Grand Total are **computed live in JS** from row-level data — no need to manually update totals.

---

## 📂 File Structure

```
Dhurandhar/
├── index.html      # Entire dashboard (CSS + JS + data inlined)
└── README.md       # This file
```

---

## 🎨 Design Notes

- **Hero**: Navy gradient (#1a1a2e → #0f3460) with fire-gold title text for visual impact on group chats
- **ME FW palette**: Orange (#e85d04 / #ff8c00) — fire / face wash heat
- **EB palette**: Green (#0c8a52 / #2bb673) — growth / emerging
- **Achievement bands**:
  - 🟢 ≥ 100% — Crossed (green pill)
  - 🟡 60–99% — On track
  - 🟠 40–59% — Slow
  - 🔴 < 40% — Critical

---

## 📞 Owner

**Maintained by :**

Sonu Saifi
Sr. Channel Insights Analyst
Honasa Consumer Limited

For corrections or new data uploads, ping on the Corporate LT WhatsApp group.

---

*Battle for leadership. Every line billed is a step to victory.* ⚔️
