<div align="center">

<!-- Pixel/arcade style ASCII banner -->
```
██╗  ██╗███████╗███╗   ██╗ ██████╗ ███████╗ █████╗ ██╗     ██╗
╚██╗██╔╝██╔════╝████╗  ██║██╔═══██╗██╔════╝██╔══██╗██║     ██║
 ╚███╔╝ █████╗  ██╔██╗ ██║██║   ██║█████╗  ███████║██║     ██║
 ██╔██╗ ██╔══╝  ██║╚██╗██║██║   ██║██╔══╝  ██╔══██║██║     ██║
██╔╝ ██╗███████╗██║ ╚████║╚██████╔╝██║     ██║  ██║███████╗███████╗
╚═╝  ╚═╝╚══════╝╚═╝  ╚═══╝ ╚═════╝ ╚═╝     ╚═╝  ╚═╝╚══════╝╚══════╝
```

**A side-scrolling arcade shooter for Android — built to bring back that feeling.**

![Platform](https://img.shields.io/badge/platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Framework](https://img.shields.io/badge/React_Native-Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Language](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Status](https://img.shields.io/badge/status-Active_Development-FF6B35?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-22C55E?style=flat-square)

</div>

---

## The Origin

**2012.** Freshly graduated, but the boredom started long before that.

Being a teenager meant two modes: bored in class or bored at home. One evening after school I made a trade — iPhone out, Android in, a hundred bucks in hand. Sat down, scrolled through the phone, spotted a game that came pre-installed. Clicked it open out of curiosity.

That was it. Hooked from the first session.

Within weeks the game was everywhere. Everyone was playing it in the halls, at lunch, on the bus. Something that started as a random click after a dull afternoon had become a cultural moment for an entire generation of teens.

That feeling never left me.

---

## The Mission

XENOFALL is built to give that feeling back — not a remake, not nostalgia bait. A new game that hits the same nerve: immediately playable, instantly addictive, the kind of thing you find on a random Tuesday and can't put down by Thursday.

> *If one kid picks up XENOFALL on a boring evening and it plants something in them — a curiosity about how games are built, a spark toward making something of their own — that's the real win.*

---

## Gameplay

A fast, sharp side-scrolling arcade shooter built to run on anything.

- ⚡ **Fluid rendering** via React Native Skia — frame-perfect movement at any speed
- 👾 **Escalating enemy waves** with intentional difficulty curves and gap spacing
- 🏙️ **Street-level visuals** — environment inspired by Atlanta's Edgewood Avenue
- 🔓 **Earn everything through play**, no paywalls
- 🎵 Soundtrack and art style rooted in real culture

---

## Stack

| Layer | Technology |
|---|---|
| Framework | React Native + Expo |
| Language | TypeScript |
| Rendering | React Native Skia |
| State Management | Zustand |
| Backend | Firebase |
| Monetization | RevenueCat |

---

## Project Structure

```
xenofall/
├── src/
│   ├── game/
│   │   ├── store/          # Zustand game state
│   │   ├── entities/       # Player, enemies, projectiles
│   │   ├── systems/        # Physics, collision, camera
│   │   └── renderer/       # Skia draw calls
│   ├── screens/            # App navigation screens
│   ├── assets/             # Sprites, audio, fonts
│   └── config/             # Game constants, difficulty config
├── app.json
└── package.json
```

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/yourusername/xenofall.git
cd xenofall

# Install dependencies
npm install

# Start the Expo dev server
npx expo start

# Run on Android
npx expo run:android
```

> **Requirements:** Node.js 18+, Android Studio (for emulator), Expo CLI

---

## Development Status

| Phase | Description | Status |
|---|---|---|
| Phase 1 | Core game loop, camera, enemy systems | ✅ Complete |
| Phase 2 | Level design, wave config, boss patterns | 🔄 In Progress |
| Phase 3 | Audio, VFX, polish pass | 🔜 Upcoming |
| Phase 4 | Beta testing, Play Store submission | 🔜 Upcoming |

---

## Built By

**Tahzjeen-Amir** — designer, developer, and a kid who once traded a phone for a hundred dollars and accidentally found a reason to build things.

---

<div align="center">

*Built for every teenager who ever sat in class wishing time would move faster.*

</div>
