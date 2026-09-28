# ⚔️ VGCHelper

### A lightweight competitive toolkit for Pokémon Champions VGC

[![Live App](https://img.shields.io/badge/🌐_Live_App-VGCHelper-dc4b4b?style=for-the-badge)](https://caioklein.github.io/VGCHelper/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge\&logo=github)](https://github.com/caioklein/VGCHelper)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge)](LICENSE)

**VGCHelper** is a fast, browser-based companion for Pokémon Champions competitive play.

Look up Pokémon, understand matchups, inspect competitive sets, test OHKO threats, and build teams from real tournament compositions: all from one place.

I was tired of bad type advantage charts and having to rely on calculators that ask just too much when we know that every sneasler, charizard and other meta pokémons are always EV specced in a certain way, so why just not assume the worst and have the damage calculator be really simple?

Oh and also you can plan teams here, just choose your favorite pokémon and the tool suggests actually good teams instead of guessing or trying to build one that doesn't make sense.

> **Less tabs needed for 10x more information**

---

## 🌐 Try It

**[→ Open VGCHelper](https://caioklein.github.io/VGCHelper/)**

No installation. No account. No backend.
Open it and start building.

---

## ✨ What can it do?

### 🔎 Pokémon Search

Quickly look up a Pokémon and get its competitive information at a glance:

* Types and type interactions
* Base stats
* EV spreads
* Natures
* Abilities
* Competitive movesets
* Held items
* Current and previous regulation data

Competitive data currently covers **Pokémon Champions Regulation M-C, M-B and M-A**.

---

### 📊 Type Matchups

A full interactive type chart with hoverable matchup information.

Need to know what a Pokémon is weak to?

Pick its types and instantly see:

**⚡ Weaknesses · 🛡️ Resistances · 🚫 Immunities**

The dual-type checker lets you combine two types and calculates their combined defensive multipliers automatically.

---

### ⚔️ Battle Box

Drag Pokémon directly into the Battle Box and check offensive threats against them.

VGCHelper calculates damage using the selected competitive configuration and reports results such as:

* 💀 Guaranteed OHKO
* ⚠️ Possible OHKO
* 🛡️ Safe
* 🚫 Immune

It also accounts for common competitive modifiers such as STAB, type effectiveness, held items and spread-move damage in Doubles.

Switch between **Doubles** and **Singles** battle calculations from the interface.

---

### 🧩 Team Planner

Start with a Pokémon — or several — and VGCHelper searches its collection of real tournament teams for compositions containing your picks.

Rather than inventing random "good partners", suggestions come from **actual VGCPastes team rosters**, with available set information, items, tournament details and source links.

You can even:

**Pick → Explore → Expand → Use the full team**

The planner supports up to six Pokémon and surfaces the remaining team members as you build.

---

### ⭐ Meta Picks

Not sure where to start?

Pin the **top 20 most-used Pokémon from Regulation M-C usage data** with a single click and start exploring the current metagame.

---

## 🧠 Built for Competitive Play

VGCHelper is designed around the stuff you actually need during team building and matchup prep:

```text
"What's good right now?"
        ↓
   Meta Picks

"What beats this?"
        ↓
   Type Checker

"Will this KO?"
        ↓
   Battle Box

"What should I pair with it?"
        ↓
   Team Planner

"How are people actually playing it?"
        ↓
   Competitive Sets
```

One tool. One screen. Less spreadsheet archaeology.

---

## 🛠️ Tech

VGCHelper intentionally keeps the stack extremely small:

* **HTML**
* **CSS**
* **Vanilla JavaScript**
* **No framework**
* **No build system**
* **No backend**
* **No dependencies**

Everything runs client-side, making the project easy to inspect, fork, modify and host.

---

## 🚀 Run Locally

Clone the repository:

```bash
git clone https://github.com/caioklein/VGCHelper.git
cd VGCHelper
```

Then simply open:

```text
index.html
```

Or serve it locally:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

That's it.

---

## 📚 Data & Sources

Competitive information is based on publicly available community data.

**Competitive sets**

* [Pikalytics](https://pikalytics.com/)
* [VGCPastes](https://vgcpastes.com/)

VGCHelper currently uses Pikalytics data for competitive usage/ranking information and aggregates common EV spreads and natures from tournament teams archived through VGCPastes.

The type chart reflects current core-series mechanics.

---

## 🎨 Design Goals

VGCHelper was built around a few simple ideas:

**Fast.**
You shouldn't need five websites open to answer one question.

**Readable.**
Competitive information should be useful at a glance.

**Practical.**
Tools should help with actual team building and matchup preparation, not just display data.

**Lightweight.**
A competitive helper shouldn't need a massive tech stack.

---

## 🤝 Contributing

Found incorrect data?
Have an idea for a new calculator?
Want to improve the UI?

Pull requests and issues are welcome.

If you're making a larger change, opening an issue first is a good way to discuss the approach. Be wary this was heavily built using AI, so the code is very possibly bad and you may have an aneurysm so don't blame me!

---

## 📜 License

VGCHelper is licensed under the **GNU General Public License v3.0**.

See [LICENSE](LICENSE) for the full license text.

---

## ⚠️ Disclaimer

VGCHelper is an unofficial, non-commercial fan project.

Pokémon, Pokémon Champions, Pokémon GO, the Pokémon logo and related names and marks are trademarks of Nintendo, Creatures Inc., GAME FREAK Inc. and/or The Pokémon Company.

VGCHelper is **not affiliated with, endorsed by, sponsored by, or approved by** Nintendo, Creatures Inc., GAME FREAK Inc. or The Pokémon Company.

---

<p align="center">

### ⚔️ Build better teams. Understand the matchup. Battle smarter.

**[🌐 Launch VGCHelper](https://caioklein.github.io/VGCHelper/)**

</p>
