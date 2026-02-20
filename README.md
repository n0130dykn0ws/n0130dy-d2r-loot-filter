```
╔══════════════════════════════════════════════════════════════════╗
║  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  ║
║  ░                                                            ░  ║
║  ░        ⛧  n 0 1 3 0 d y   v 1 . 3  ⛧                     ░  ║
║  ░          D I A B L O  I I  R E S U R R E C T E D          ░  ║
║  ░               S E A S O N  1 3  L A D D E R               ░  ║
║  ░                    L O O T  F I L T E R                    ░  ║
║  ░                                                            ░  ║
║  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  ║
╚══════════════════════════════════════════════════════════════════╝
```

> *"Not all that glitters is worth your time. Not all that hides is worthless."*

A single-file progressive loot filter for Diablo II Resurrected built for the **Season 13 Ladder Reset**. Designed to evolve with you — from fresh character to full endgame — by toggling off rules as you progress rather than swapping between multiple filter files.

---

## ⛧ Installation

### Method 1 — Copy & Paste (Easiest)
1. Click `n0130dy_v1.3.json` in this repo
2. Click the **Copy raw file** button (top right of the file view)
3. In-game: `ESC` → `Loot Filter` → **Create New Filter**
4. Paste the code in, save it, and you're done

### Method 2 — File Download
1. Download `n0130dy_v1.3.json`
2. Place it in your D2R loot filter directory:
   - **Windows:** `%UserProfile%\Saved Games\Diablo II Resurrected\`
3. In-game: `ESC` → `Loot Filter` → select **n0130dy v1.3**

---

## ⛧ Keybinds

> Configure these in `Settings > Keybinds`

| Key | Action |
|-----|--------|
| `Ctrl + Alt` | Show Items Toggle — toggles filter on/off |
| `Alt` | Show Items Unfiltered Hold — hold to reveal all items, ignores filter |

---

## ⛧ How It Works

This filter uses a **single Hide All rule** at the bottom (Rule 23) that catches everything. Every other rule is a **Show rule** that punches holes through it for specific items.

- **Unchecking a Show rule** → those items become hidden
- **Rule 23 must never be disabled** — it is the foundation everything rests on
- Rule order does not matter — Show always beats Hide in D2R

As you progress, you simply uncheck rules you no longer need. No new files. No re-importing.

---

## ⛧ Progression Guide

```
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
  STAGE              ACTION
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
  Fresh Character    All rules ON — see everything
  After Act 2        Uncheck Rule 1  (Show All)
  Enter Nightmare    Uncheck Rule 2  (All Potions)
                     Uncheck Rule 3  (Keys & Scrolls)
  Enter Hell         Uncheck Rule 4  (Socketed Armor)
                     Uncheck Rule 5  (Socketed Weapons)
                     Uncheck Rule 6  (Magic Jewelry)
  Farming Hell       Uncheck Rule 7  (Rare Class Items)
  Optional           Uncheck Rule 11 (Arrows & Bolts)
                     — disable if not Amazon or ranged Warlock
  ⚠️ NEVER           Disable Rule 23 — ever
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
```

There is no wrong pace. Uncheck rules when the items feel like clutter, not on a strict schedule.

---

## ⛧ Full Rule Breakdown

### 🩸 Leveling Rules — Toggle Off As You Progress

| # | Rule | What It Shows | Disable When |
|---|------|--------------|--------------|
| 1 | Show All | Every item on the ground | Leaving Act 1 |
| 2 | All Potions | All HP and MP potions (hp1–hp5, mp1–mp5) | Entering Nightmare |
| 3 | Keys & Scrolls | ID scrolls, TP scrolls, keys | Entering Nightmare |
| 4 | Socketed Armor | Any socketed armor (all tiers) | Entering Hell |
| 5 | Socketed Weapons | Any socketed weapon (all tiers) | Entering Hell |
| 6 | Magic Jewelry | Magic rings and amulets | Entering Hell |
| 7 | Rare Class Items | Rare items for all 8 classes | Full endgame geared |

---

### ☠️ Always-On Rules — Never Disable These

| # | Rule | What It Shows |
|---|------|--------------|
| 8 | Runes, Ubers, TZ, Absolutes | All runes, uber keys, terror zone drops, worldstone shards, colossal statues |
| 9 | All Gems & Skulls | Every gem and skull at every quality |
| 10 | Gold 5000+ | Gold piles worth 5,000+ |
| 11 | Arrows & Bolts | All ammunition |
| 12 | Rejuvenation Potions | Full and small rejuvs |
| 13 | Max HP/MP Potions | Super healing (hp5) and super mana (mp5) only |
| 14 | All Uniques | Every unique item — no exceptions |
| 15 | All Sets | Every set item — no exceptions |
| 16 | All Charms | Every charm |
| 17 | All Jewels | Every jewel |
| 18 | Rare Rings & Amulets | All rare rings and amulets |
| 19 | Rare Gloves, Boots, Belts | Rare gloves, boots, belts, circlets, wands, orbs, claws, and high-value weapon bases |
| 20 | Magic Orbs, Helms, Wands | Magic orbs, druid pelts, barb helms, necro heads, circlets, wands — crafting and gambling targets |
| 21 | Elite Socketed Armor | All elite armor bases with sockets — runeword targets |
| 22 | Elite Socketed Weapons | All elite weapon bases with sockets — runeword targets, includes dagger bases for Void |
| 23 | ⚠️ Hide All — NEVER DISABLE | The foundation. Hides everything not explicitly shown above |

---

## ⛧ Design Philosophy

- **One file. One filter. No swapping.**
- Conservative on new expansion content — unverified item codes stay out until tested
- All Warlock uniques and sets show automatically via rules 14 & 15
- New runeword dagger bases (Legend Spike, Stiletto) included in rule 22
- Tested and validated for Season 13 with Reign of the Warlock expansion content

---

## ⛧ Credits

Built with the community in mind. Referenced filters from **MrLlamaSC** and the broader D2R filter community. Shared across the D2R community for Season 13.

---

```
╔══════════════════════════════════════════════════════════════════╗
║  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  ║
║  ░      May your runes be plentiful and your bases clean.     ░  ║
║  ░                  Good luck on the reset.                   ░  ║
║  ░                        ⛧  ⛧  ⛧                            ░  ║
║  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  ║
╚══════════════════════════════════════════════════════════════════╝
```
