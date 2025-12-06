# 3D Coin — Simple Coin Flip Betting Game

![Screenshot](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhZWZnVu4l9dMo-wGSaWQGAoVKDTPPsWcA0zwbMEJHnNH3ctprFtdFbEjcNzbjxWR-q2ADvQ7o_zGUqz0qmtYJGb5dupEhAq4VXQBP-lHxstluVmPnK6TgDyODG88ex1th4G68OpelU9_bebrZ1Aq7N1L2cm_WQq5UrXNksNkjyHTvTaHTnJ91qm8adi4Fp/s1080/1000394654.jpg)

**3D Coin** is a small coin-flip style betting game. Players bet up to **10** (units) and flip a 3D coin. One side reads **YES**, the other **NO** — if the result matches the player's choice, they win; otherwise they lose. Simple, fast, and ideal for quick demos or small arcade-style projects.

---

## How it works
- Player chooses a side: **YES** or **NO**.  
- Player places a bet (1–10 units).  
- The coin is flipped (3D animation).  
- If the coin lands on the chosen side, the player wins the bet (payout is configurable).  
- If not, the player loses the bet.

> This game is intended for demo / entertainment purposes. Do not use with real money where gambling is restricted or regulated.

---

## Features
- 3D coin animation (WebGL / Unity / Three.js friendly)  
- Simple betting UI (min/max bet enforcement)  
- Instant win/lose feedback and result history  
- Lightweight and easy to integrate into other projects

---

## Gameplay Rules (default)
- Min bet: 1 unit  
- Max bet: 10 units  
- Payout: (configurable) — default is 1:1 (win returns original bet + equal amount)  
- No house edge by default — change logic in code to apply commission or odds.

---

## Quick Start (Web / Three.js example)
1. Clone the repo.
2. Open `index.html` or serve the `web/` folder.
3. Choose **YES** or **NO**, set bet (1–10), then press **Flip**.

```bash
git clone <repo-url>
cd 3d-coin
# either open web/index.html directly or run a static server
# python 3:
python -m http.server 8080
# then open http://localhost:8080/web/
