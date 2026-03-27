# SNAPSPUNK-FALLOUT4

![Banner Image](link-to-banner-image)

>[!IMPORTANT]
>- SNAPSPUNK-FALLOUT4 requires all **official DLC** (except High Definition DLC).
>- This list uses a specific game version - read the requirements carefully.

>[!WARNING]
>You must own **Fallout 4 on Steam** (not GOG, not Epic) to install this list.

---

## Table of Contents

- [Introduction](#introduction)
- [System Requirements](#system-requirements)
- [Pre-Installation](#pre-installation)
- [Installation](#installation)
- [Post-Installation](#post-installation)
- [Updating the Modlist](#updating-the-modlist)
- [Profiles](#profiles)
- [Keybinds](#keybinds)
- [Known Issues](#known-issues)
- [Credits](#credits)
- [Contact & Support](#contact--support)

---

## Introduction

**SNAPSPUNK-FALLOUT4** is a story-driven, tactical overhaul of *Fallout 4* designed for players who want a challenging, immersive Commonwealth experience. Combat is lethal, survival requires strategy, and every choice shapes your story.

### Design Philosophy

- **Story-Driven**: Enhanced narrative with roleplay-focused dialogue and quest mods
- **Tactical Gameplay**: Smarter AI, realistic combat, meaningful weapon choices
- **Flexible Settlement Options**: Choose between Sim Settlements 2 city builder or traditional manual settlements
- **Visual Excellence**: Carefully curated visuals that enhance the post-apocalyptic atmosphere

### Features

- **Combat**: Tactical AI, realistic ballistics, weapon handling overhauls
- **AI**: Enhanced enemy tactics, improved companion behavior
- **Story**: Expanded quests, dialogue overhauls, faction improvements
- **Settlements**: Choose your playstyle with dual profiles
- **Visuals**: Lighting, weather, and texture improvements
- **Audio**: Weapon sounds, environment ambience, music options

---

## Choose Your Profile

SNAPSPUNK-FALLOUT4 includes two profiles for different settlement playstyles:

### Profile 1: Sim Settlements 2
- Full city builder experience
- Automated settlement growth and management
- Story-driven settlement quests (SS2 Chapters)
- Pre-built city plans available
- Ideal for players who want living, breathing settlements

### Profile 2: Traditional Settlements
- Manual workshop building
- Classic settlement experience
- Expanded workshop objects and tools
- No Sim Settlements dependencies
- Ideal for players who prefer hands-on control

Both profiles share the same core gameplay, combat, story, and visual mods.

---

## System Requirements

> [!WARNING]
> - You need an **official** copy of *Fallout 4* on **Steam** with all DLC.
> - An **SSD is required** — do not try to run this on an HDD.
> - Only **Windows 10/11** is supported.
> - **High Definition DLC is NOT required** (and not recommended).

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| CPU | [CPU] | [CPU] |
| GPU | [GPU] | [GPU] |
| RAM | [RAM] | [RAM] |
| Storage | [Storage] SSD | [Storage] SSD |

<details>
<summary><strong>Size Breakdown</strong></summary>

- **Base Game + DLC:** ~XX GB
- **Modlist Downloads:** ~XX GB
- **Modlist Install Size:** ~XX GB

**Modlist Total:** ~XX GB
**Overall Space Required:** ~XX GB

</details>

---

## Pre-Installation

> Screenshots and instructions below assume you're using the **Steam version**.

### 1. Clean Install

1. Uninstall Fallout 4 through Steam
2. Delete the game folder
3. Delete the `Fallout 4` folder in `Documents/My Games/`
4. Reinstall Fallout 4 on Steam
5. **Launch the game once** to establish registry paths

### 2. Visual C++ Redistributables

Install the following from Microsoft:

- [Visual Studio 2015, 2017, 2019, and 2022 (x64)](https://aka.ms/vs/17/release/vc_redist.x64.exe)
- [Visual Studio 2012 (VC++ 11.0) Update 4 (x64)](https://download.microsoft.com/download/1/6/B/16B06F60-3B20-4FF2-B699-5E9B7962F9AE/VSU_4/vcredist_x64.exe)

### 3. Steam Configuration

<details>
<summary>Disable Auto-Updates</summary>

1. Right-click *Fallout 4* in your Steam Library > **Properties**
2. Go to the **Updates** tab
3. Set Automatic Updates to **"Only update this game when I launch it"**
4. From now on, **only launch the game through Mod Organizer 2**.

</details>

<details>
<summary>Set Language to English</summary>

1. Right-click *Fallout 4* in your Steam Library > **Properties**
2. Go to the **Language** tab
3. Set Language to **English**

> This modlist is in English and support is only provided for English game versions.

</details>

### 4. DLC Requirements

Ensure the following are installed:
- Fallout 4
- Automatron
- Wasteland Workshop
- Far Harbor
- Contraptions Workshop
- Vault-Tec Workshop
- Nuka-World
- **Phantom Liberty** (if applicable)

> ❌ Do NOT install the High Definition DLC - it causes issues and provides minimal benefit.

### 5. Additional Runtimes

- Install [.NET Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/9.0) (latest version)
- Install [DirectX End-User Runtime](https://www.microsoft.com/en-us/download/details.aspx?id=35)

---

## Installation

### Wabbajack Installation

1. **Download [Wabbajack](https://www.wabbajack.org)** and place it in a dedicated folder at the root of a drive.
   
   Example: `C:\Wabbajack\Wabbajack.exe`

2. Launch **Wabbajack** and go to **Browse Modlists**.

3. Search for **SNAPSPUNK-FALLOUT4** in the Fallout 4 section.

4. Click the cover art, then download and install.

5. Set your paths:
   - **Installation:** `D:\Wabbajack\SNAPSPUNK-FALLOUT4`
   - **Downloads:** `D:\Wabbajack\downloads`

   > ⚠️ Both folders should be on an SSD. They can be on separate drives.

6. Hit **Install** and let Wabbajack do its thing.

7. Once complete, open the install folder and launch `ModOrganizer.exe`.

8. Select your desired profile (**Sim Settlements 2** or **Traditional**), then hit **Run**.

---

## Post-Installation

### Antivirus Configuration

> [!WARNING]
> Antivirus software (especially BitDefender, Norton, Webroot) will cause problems with MO2's Virtual File System. You may need to add exclusions or disable third-party antivirus.

<details>
<summary>How to add a Windows Defender exception</summary>

1. Open **Windows Security**
2. Go to **Virus & threat protection**
3. Click **Manage settings**
4. Scroll to **Exclusions** > **Add or remove exclusions**
5. Add your SNAPSPUNK-FALLOUT4 installation folder

</details>

### Overlays

Disable any overlays — Steam overlay, Discord overlay, GPU software overlays, Xbox Game Bar, etc.

### Initial Setup

1. Launch MO2
2. Select your desired profile
3. Run the game from MO2 (not Steam)
4. Configure MCM settings as desired (see MCM Recommendations below)

<details>
<summary>MCM Recommendations</summary>

[Add MCM configuration recommendations here]

</details>

---

## Updating the Modlist

1. Download the latest `.wabbajack` file from the Wabbajack gallery.
2. Run the installer and point it to your existing installation.
3. **Check the `Overwrite` box** before installing.
4. Your mods marked with `[NoDelete]` prefix will be preserved.

> [!WARNING]
> Wabbajack will delete all files that are not part of the modlist when updating!

### Version Numbering

This modlist uses semantic versioning:
- **x.0** (e.g., 2.0, 3.0) - Major update, requires new game
- **x.x** (e.g., 2.1, 2.2) - Minor update, may require new game
- **x.x.x** (e.g., 2.1.1, 2.1.2) - Patch update, safe for existing saves

---

## Profiles

### Sim Settlements 2 Profile

This profile includes the full Sim Settlements 2 experience:

**Included:**
- Sim Settlements 2 Core + Chapters 1, 2, 3
- Industrial Revolution
- Rise of the Commonwealth
- City Plans for major settlements
- Plot packs and add-ons

**Getting Started:**
1. Complete the initial SS2 tutorial quest
2. Check the MCM for SS2 settings
3. Visit the City Planner desk in your chosen settlement
4. Choose a city plan or build manually with plots

### Traditional Settlements Profile

This profile uses manual workshop building:

**Included:**
- Workshop Framework
- Place Everywhere
- Expanded settlement boundaries
- Additional workshop objects
- Scrap Everything (optional)

**Getting Started:**
1. Enter workshop mode at any settlement
2. Build as you would in vanilla, with expanded options
3. Use Place Everywhere for precise object placement

### Switching Profiles

1. Open MO2
2. Click the profile dropdown (top right)
3. Select your desired profile
4. Click **Run** to launch the game

---

## Keybinds

| Key | Action | Mod |
|-----|--------|-----|
| `[Key]` | [Action] | [Mod Name] |
| `[Key]` | [Action] | [Mod Name] |

Check each mod's page for additional keybind options and MCM settings.

---

## Known Issues

- [List known issues here]

---

## Adding Custom Mods

You can add your own mods on top of SNAPSPUNK-FALLOUT4. To prevent Wabbajack from removing them during updates:

1. Rename your mod to start with `[NoDelete]`
2. Place it under the `📌 [NoDelete] - Personal Mods` separator

---

## Widescreen Support

For ultra-wide monitors (32:9 or 21:9):

- [Super Ultra Wide Interface 32:9](https://www.nexusmods.com/fallout4/mods/56363)
- [Ultra Wide Interface 21:9](https://www.nexusmods.com/fallout4/mods/65677)

> Note: You need the NON-Next-Gen version of these mods.

---

## Credits

### Mod Authors

This modlist would not be possible without the incredible work of the Fallout 4 modding community. Special thanks to all mod authors whose work is included.

### Key Frameworks

- **F4SE** - F4SE Team
- **Buffout 4 NG** - [Author]
- **High FPS Physics Fix** - [Author]
- **Mod Configuration Menu** - [Author]
- **FallUI** - [Author]

### Settlement Frameworks

- **Sim Settlements 2** - Kinggath and team
- **Workshop Framework** - [Author]

---

## Contact & Support

- **Discord**: [Server Link]
- **GitHub Issues**: [Repository Link]
- **Load Order**: [LoadOrderLibrary Link]

### Before Asking for Help

1. Read this README in full
2. Check the FAQ (if available)
3. Verify your game version matches the list requirements
4. Check for conflicts with any mods you've added

---

## Donate

If you enjoy this modlist, consider supporting its development:

- [Patreon]
- [Ko-fi]

---

**War Never Changes. But Your Story Does.**

*SNAPSPUNK-FALLOUT4*
