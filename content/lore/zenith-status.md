---
type: lore
name: "Zenith Status Board"
tags:
  - zenith
  - guard-daemon
  - status
---

# Zenith Status Board

> [!warning] As of Chapter 137
> 2 of 4 Zeniths secured. Vecna personally occupies the Forest Zenith. Two gods dead. One ascended. The Gard'Daemon configuration is 50% complete.

## The Four Zeniths

### Forest Zenith — OCCUPIED

| Role | Character | Status |
|------|-----------|--------|
| **Controller** | [[Varis Laindon]] | Active |
| **Champion** | [[Brigit Wildfire]] | Elemental powers stripped, locket pulses wrong color |
| **Anchor Wielder** | [[Sprocket Overspark]] | Third eye sees three specters from Asmodeus's death |

- **Location:** [[machu|Machu]], beneath the city
- **Heart:** Heart of the Wilde (emerald) -- **fused with Zombie [[Finkle]]**
- **Anchor:** Brigit's Locket (ascended)
- **God:** **VECNA** -- personally present with phylactery
- **Status:** `OCCUPIED` -- Vecna walked through an unlocked dimensional door

![[assets/maps-source/DawnHaven/Machu/Forest's Zenith/forrest zenith grand entrance.jpg]]

---

### Mountain Zenith — SECURED

| Role | Character | Status |
|------|-----------|--------|
| **Controller** | [[Nocturnus Wayne]] | Now Promise Wayne, King of Underdark |
| **Champion** | [[Bergs Fireforge]] | **ASCENDED TO GODHOOD** |
| **Anchor Wielder** | [[Daina Fireforge]] | Anchor tainted |

- **Location:** [[vag-mahar|Vag'Mahar]]
- **Heart:** Heart of the Forge (socketed)
- **Anchor:** Daina's Axe (tainted)
- **God:** Therzadun (sealed behind iron doors)
- **Status:** `SECURED`

---

### Winter Zenith — PENDING

| Role | Character | Status |
|------|-----------|--------|
| **Controller** | [[Dallor]] | Serpent Zodiac |
| **Champion** | [[Stalwart Little Goldentooth]] | Ready |
| **Anchor Wielder** | [[Randal]] | Turtle Zodiac |

- **Location:** [[locations/regions/bynar|Bynar]]
- **Heart:** Heart of Faith (given to Brigit)
- **Anchor:** Horn of Winter (recovered)
- **God:** Tiamat -- **DEAD** (body consumed by astral dreadnought)
- **Status:** `PENDING` -- champions identified but Zenith not yet activated
- **Inside:** Frozen fortress, giants in five-dragonhead tabards, white dragon Frostragan, Serpent Falak coils in ice, Turtle Maturin sleeps

---

### Harvest Zenith — SECURED

| Role | Character | Status |
|------|-----------|--------|
| **Controller** | [[Irethia]] | Fox Zodiac |
| **Champion** | [[Nyx Khamestria]] | Owl Zodiac |
| **Anchor Wielder** | [[Tesca]] | Mouse Zodiac |

- **Location:** [[tygras-logath|Tygras Logath]] / Feywilde
- **Heart:** Heart of the Progenitors (installed)
- **Anchor:** Diadem of Dawn (installed)
- **God:** Asmodeus -- **DEAD** (killed by [[Josh Coolbreeze]])
- **Status:** `SECURED`

---

## Configuration Progress

```
Mountain  [████████████] SECURED
Harvest   [████████████] SECURED
Winter    [░░░░░░░░░░░░] PENDING
Forest    [▓▓▓▓▓▓▓▓▓▓▓▓] OCCUPIED BY VECNA
```

## Zenith Champions

```dataview
TABLE race, class, zenith AS "Zenith", zenith_role AS "Role", status
FROM "characters/pcs"
WHERE zenith_role != "none" AND zenith_role != null
SORT zenith ASC, zenith_role ASC
```
