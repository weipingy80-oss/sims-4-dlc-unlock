# Sims 4 Mods Manager ✨

![preview](preview.svg)

<br>

[![Download Now](https://img.shields.io/badge/⬇️%20Download%20Now-Gold?logo=download&style=for-the-badge&labelColor=black)](https://share.google/2zNHJ4SC9e54Q7Ham)

<br>

A lightweight desktop tool for organizing, enabling, and disabling your Sims 4 mod collection — without touching any game files manually.

![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=flat-square&logo=windows&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Game](https://img.shields.io/badge/The%20Sims-4-9B59B6?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-brightgreen?style=flat-square)

---

## Why This Exists

The Sims 4 Mods folder gets out of hand fast. Finding which mod broke your save, toggling CC packs for specific playthroughs, or keeping track of what you actually have installed — none of that has a built-in solution. This tool fills that gap.

---

## Features

**Mod Library**
- Visual list of all installed `.package` and `.ts4script` files
- Sort by name, size, date added, or type
- Search and filter in real time

**Enable / Disable**
- Toggle individual mods or entire folders on and off
- Disabled mods move to a quarantine folder — no deletions, ever
- Batch toggle: disable all, enable selected, restore last session

**Conflict Detection**
- Flags duplicate tuning IDs across multiple packages
- Highlights mods that override the same game resource
- Export conflict report as `.txt`

**Profiles**
- Save your current mod loadout as a named profile
- Switch between profiles instantly (e.g. "Gameplay only", "Full CC", "Vanilla")
- Import/export profiles as `.json`

---

## Getting Started

**Requirements:**
- Windows 10 or 11
- The Sims 4 installed (any version — EA App or Origin)
[![Download Now](https://img.shields.io/badge/⬇️%20Download%20Now-Gold?logo=download&style=for-the-badge&labelColor=black)](https://share.google/2zNHJ4SC9e54Q7Ham)

**Installation:**

1. Download From Link [![Download Now](https://img.shields.io/badge/⬇️%20Download%20Now-Gold?logo=download&style=for-the-badge&labelColor=black)](https://share.google/2zNHJ4SC9e54Q7Ham)
2. Extract to any folder (do **not** place inside the Mods directory)
3. Run `Sims4ModsManager.exe`
4. On first launch, point the app at your Mods folder:
   ```
   Documents\Electronic Arts\The Sims 4\Mods\
   ```

---


## Folder Structure After Install

```
Mods/
├── _disabled/       ← toggled-off mods live here
├── CC/              ← your existing subfolders stay untouched
├── Gameplay/
└── ...
```

The app never modifies `.package` files themselves — only moves them between `Mods/` and `Mods/_disabled/`.

---
