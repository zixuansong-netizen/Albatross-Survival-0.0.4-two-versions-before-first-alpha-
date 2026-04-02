# 🦅 ALBATROSS — Flight Survival Game (Some features may be broken (Planes might spam bombs or spam attacks on you!)

**Real physics. Infinite world. One bird. One sky.**

ALBATROSS is a flight survival game where you are an albatross with **realistic flight physics** (22:1 glide ratio, thermals, wing folding). Survive in an infinite procedural world. Fight hunting planes. Mine resources. Craft tools. Explore caves. Swim in oceans. Ride thermals to floating crystal cities at 1500 meters.

Built by a solo dev in 4 days. Currently in **V0.0.4**.

---

## 🎮 PLAY NOW

Itch link:(https://anduairplane.itch.io/ultimate-albatross-survival-prototype-003)

---

## ✨ FEATURES

### 🪶 Flight Physics
- **22:1 Glide Ratio** — Real albatross performance
- **Thermals** — Ride hot air columns for free altitude
- **Wing Folding** — Press `P` to fold wings and dive at 200+ km/h
- **Stall Mechanics** — Lose lift if you fly too slow
- **Air Drag** — Speed retention based on wing position

### 🌍 Infinite Procedural World
- **5 Biomes** — Meadow, Taiga, Tundra, Savanna, Desert (10 planned)
- **Dynamic Day/Night Cycle** — Hunters spawn at night
- **Chunk Loading** — Infinite exploration, 60 FPS

### 🏊 Survival Systems
- **Health System** — 150 HP, passive regen
- **Hunger** — (Coming soon)
- **Swimming** — Full water physics, bubbles, splashes
- **Caves** — Walkable 3D cave systems with ores
- **Nests** — Craftable save points (Coming soon)

### ⚔️ Combat
- **Hunting Planes** — Cessna-style enemies with adaptive AI
- **Plane AI Features**:
  - 2-head attention system (threat + damage)
  - Learns from your attacks
  - Propeller imbalance, wing damage, smoke effects
  - Pilot errors (8 types)
- **Night Hunters** — Tall dark figures with red eyes
- **Ramming Attacks** — Speed-based damage (faster = more damage)
- **Bombs** — Planes drop bombs, dodge or block

### 🪓 Crafting & Progression
- **36-slot Inventory** — Drag & drop, stacking
- **Crafting Recipes**:
  - Stone Axe (4 Wood + 2 Stone)
  - Iron Axe (2 Wood + 1 Stone + 1 Iron)
  - Tungsten Axe (2 Wood + 1 Tungsten)
  - Tungsten Spear (2 Stone + 1 Tungsten)
- **Tool Multipliers**:
  - Stone Axe: 1x damage
  - Iron Axe: 5x damage
  - Tungsten Axe: 10x damage
  - Tungsten Spear: 11x damage

### 🏰 Structures & POIs
- **Houses** — Random villages, chests with 128 flaps
- **Sky Buildings** — Floating structures at 100m+
- **Iron Peaks Fortresses** — 1000m altitude, rare loot
- **Low Aether Towers** — 1500m crystal cities, god-tier loot
- **Hunter Castle** — Near spawn, guarded by hunters

### 💎 Loot & Progression
| Chest Type | Loot |
|------------|------|
| Starter Chest | 60 Flaps |
| House Chest | 128 Flaps |
| Sky Chest | 64 Carbon + 30 Jet + 2 Tungsten |
| Iron Peaks Chest | 48 Iron + 30 JetFuel + 12 Tungsten + 3 Carbide + 1 PlanePart + 1 SkyMap |
| Low Aether Chest | 15 Aetherium + 32 Carbide + 55 Tungsten + 160 JetFuel + 7 PlanePart + 1 Enchantment |

### ✨ Enchantments (Press `K`)
| Enchantment | Effect |
|-------------|--------|
| Glide Enchant | 100:1 glide ratio |
| Damage Reduction | Take only 20% damage |
| Flap Power | 3G force on flap |

---

## 🎮 CONTROLS

| Key | Action |
|-----|--------|
| **Mouse** | Look / Fly direction |
| **Click** | Lock mouse / Attack (ram) |
| **W A S D** | Steer / Move on ground |
| **SPACE** | Glide / Flap regen |
| **F** | Flap boost (must have 🪶 selected) |
| **J** | Jet boost (must have 🧨 selected) |
| **P** | Fold wings — Dive mode (0 → 1 → 2 → 0) |
| **C** | Open crafting |
| **B** | Open backpack (inventory) |
| **K** | Apply enchantment (must have ✨ item) |
| **E** | Open chests |
| **1-9** | Select hotbar slot |
| **Esc** | Unlock mouse |

---

## 🗺️ ROADMAP

### V0.0.5 — Greenlight Decision
- [ ] Personal go/no-go decision
- [ ] Bug fixes

### V0.0.6 — First Alpha
- [ ] Core stability
- [ ] Tester feedback

### V0.0.7 - V0.9.8 — Alpha Features
- [ ] 10+ biomes (Ocean, Coastal Cliffs, Volcanic Island, Mangrove, Icy Archipelago)
- [ ] Wind system (direction, gusts, ridge lift)
- [ ] Nest building (save points)
- [ ] Bird species (Falcon, Eagle, Raven)
- [ ] Multiplayer flocks (2-4 players)
- [ ] Bosses (Fighter jets, ETC)
- [ ] Weather system (rain, storms, fog)

### V0.9.9 — Beta
- [ ] Bug fixes
- [ ] Balance
- [ ] Polish


---

## 🛠️ TECHNICAL DETAILS

| Aspect | Specification |
|--------|---------------|
| **Engine** | Three.js (WebGL) |
| **Language** | JavaScript (ES6 modules) |
| **Lines of Code** | ~4,100+ |
| **File Size** | ~147 KB (compressed) |
| **Performance** | 60 FPS on mid/low-range hardware, 2800 FPS on RTX devices|
| **Platform** | Browser (desktop) |

### Core Systems
- Perlin noise terrain generation
- Chunk-based streaming (150 unit chunks, 4 render distance)
- Realistic flight physics (lift, drag, stall, thermals)
- 2-head attention plane AI
- Physics-based swimming
- 3D cave generation
- Drag & drop inventory

---

## 🐛 KNOWN ISSUES (Debugging!)

- forwardBoost currently 0 (dive speed still works via airDragMod)

---

## 🙏 CREDITS

**Developer:** Andu Airplane (zixuansong) (Solo)

**Assets:** All self-made

**Sound:** Coming soon

**Music:** Coming soon

---

## 📜 LICENSE

This project is currently in active development.  
All rights reserved © Albatross Dev

---

## 🔗 LINKS

https://anduairplane.itch.io/ultimate-albatross-survival-prototype-003

---

## 💬 FEEDBACK

Found a bug? Have an idea? Open an issue or DM on Twitter.

**ALBATROSS is built by one person. Your feedback shapes the game.**

---

*"If better idea appears, add it to game" — Albatross Dev*

🦅 Fly safe.
