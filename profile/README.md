# 🌿 Plants vs. Zombies Mod Menu

The **Plants vs. Zombies Mod Menu** is a full-featured customization tool that lets players rewrite the rules of PopCap’s beloved tower defense classic. With real-time controls for sunlight, plant stats, zombie behavior, and level editing, this mod transforms the game into an open sandbox for creativity, challenge, and experimentation.

Whether you’re crafting cinematic battle setups, testing strategies, or just having fun, the Mod Menu provides a clean, responsive overlay interface designed to make every change instant and reversible.

---

## 🌻 Overview

This isn’t just a cheat — it’s a **creative toolkit**. The **Plants vs. Zombies Mod Menu** gives you control over the game’s internal mechanics: spawn rates, plant placement, zombie health, sun economy, and much more.
It’s perfect for challenge map creators, YouTubers, or casual players who want a sandbox experience with endless possibilities.

> [!IMPORTANT]
> The Mod Menu operates locally and **does not affect online leaderboards**. It’s purely for single-player experimentation and fun.

---

## 🌞 Core Features

### 🌼 Resource Management

* **Unlimited Sunlight** – never run out of planting energy.
* **Adjustable Sun Rate** – customize natural sunlight generation speed.
* **Auto Sun Collection** – instantly absorb every drop on the field.
* **Instant Recharge** – remove plant cooldowns entirely.

### 🪴 Plant Customization

* **Plant Editor Panel** – modify damage, rate of fire, and hitpoints.
* **Instant Growth Mode** – plants bloom the moment they’re placed.
* **No Plant Limit** – expand beyond the default grid layout.
* **Custom Plant Scaling** – enlarge or shrink plants for fun or difficulty.

### 🧟 Zombie Control

* **Zombie Spawner** – summon specific zombie types or full waves.
* **Adjust Zombie Speed / Health / Damage.**
* **Freeze All Zombies** – pause gameplay for testing.
* **One-Hit Kill Mode** – clear waves instantly.

### 🎨 Visual & Environment

* **Toggle Fog, Night Mode, and Pool Water.**
* **Change Background Themes** dynamically.
* **Slow Motion Mode** – cinematic time control for highlight captures.
* **Unlock All Levels, Mini-Games, and Survival Maps.**

---

## 🖥 Compatibility

| Platform        | Support        | Details                  |
| --------------- | -------------- | ------------------------ |
| Windows 10/11   | ✅ Full Support | DX9/11 overlay injection |
| Steam Version   | ✅ Yes          | Automatic detection      |
| EA App / Origin | ✅ Yes          | Manual path required     |
| Linux (Proton)  | ⚠️ Partial     | Minor overlay flicker    |

> [!NOTE]
> Launch the menu *before* starting the game for the best results.

---

## ⚡ Setup & Launch

1. Extract the `PvZ_ModMenu.zip` archive.
2. Copy the folder into your **Plants vs. Zombies** directory.
3. Run `PvZ_ModMenu.exe` as Administrator.
4. When you see:

   ```
   [✔] Game detected — Mod Menu active
   ```

   Press **F7** in-game to open the overlay.

Command-line example:

```bash
C:\Games\PlantsVsZombies\PvZ_ModMenu.exe --overlay --dx9
```

---

## 🧩 System Flow

```mermaid
flowchart TD
A[User Input (Hotkey F7)] --> B[Overlay Interface]
B --> C{Select Category}
C -->|Resources| D[Sun / Cooldown Controls]
C -->|Plants| E[Stat Editor / Scaling / Growth]
C -->|Zombies| F[Spawn / Speed / Freeze]
C -->|Visuals| G[Fog / Background / Unlocks]
G --> H[Memory Sync Engine]
```

---

## 🧠 Advanced Configuration

You can fine-tune your settings by editing `menu_config.json`:

```json
{
  "overlay_key": "F7",
  "resources": {
    "infinite_sun": true,
    "sun_rate": 2000
  },
  "plants": {
    "no_limit": true,
    "growth_speed": 3.0,
    "scale": 1.2
  },
  "zombies": {
    "spawn_type": "Gargantuar",
    "health_multiplier": 1.5,
    "speed": 0.8
  }
}
```

Profiles are saved automatically and can be loaded in-game through the *Presets* tab.

---

## ❓ FAQ

**Q1: Is the Mod Menu safe to use?**
✅ Yes. It only modifies live memory values and doesn’t alter save files or binaries.

**Q2: Can I use it in Versus or Leaderboard modes?**
❌ No. It’s designed strictly for single-player or sandbox gameplay.

**Q3: My overlay won’t show — what’s wrong?**
Run the game in **windowed borderless** mode and ensure DirectX 9 or 11 rendering is active.

**Q4: Are custom plants or mods supported?**
Yes. Compatible with most fan mods and re-skins. Load them before launching the menu.

**Q5: Does it work with HD or GOTY versions?**
✅ Fully supported. It auto-detects your build on launch.

---

## 🧾 Recommended Presets

| Profile      | Focus                 | Key Features                                    |
| ------------ | --------------------- | ----------------------------------------------- |
| *Sandbox*    | Full creative freedom | Infinite Sun, No Plant Limit, Spawn Zombies     |
| *Cinematic*  | Slow motion & visuals | Fog Toggle, Slow Time, Zombie Freeze            |
| *Challenge*  | Strategy testing      | Custom Stats, Fast Zombies, Limited Sun         |
| *Chaos Mode* | Pure fun              | Giant Plants, Random Zombie Waves, Rapid Growth |

---

## 💬 Pro Tips

> [!WARNING]
> Avoid using *One-Hit Kill* and *Zombie Spawner* simultaneously in high-wave maps — may crash due to overflow spawns.

* Combine **Instant Recharge** with **Fast Zombie Waves** for training reflexes.
* Save your favorite setups as presets to swap instantly.
* Use **Slow Motion Mode** with **Giant Plants** for fun visual experiments.

---

## 🌻 Final Thoughts

The **Plants vs. Zombies Mod Menu** gives you complete freedom over PopCap’s iconic defense game — from limitless creativity to cinematic sandboxing. It’s the definitive way to experience PvZ with no boundaries, no waiting, and total customization.

Whether you’re designing challenges or just letting chaos bloom, this tool is your all-access pass to total garden domination.

---

**Grow your power. Rewrite the rules. Command your garden with the Plants vs. Zombies Mod Menu.**
