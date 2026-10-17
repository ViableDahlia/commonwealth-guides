**Commonwealth Guides**

# How I set up a second copy of Fallout 4

| Property | Details |
| --- | --- |
| **Type** | Guide, Modding & Setup |
| **Purpose** | Run a second, fully separate copy of Fallout 4 alongside your main install |
| **Requirements** | Steam copy of Fallout 4, ~30GB free space, Mod Organizer 2, Fallout 4 Script Extender (F4SE - optional) |
| **Time needed** | 15–30 minutes |
| **Outcome** | A separate copy of Fallout 4 with its own portable MO2, preferences, saves, and mods |

---

## Why do this

Steam needn't be the boss of your updates. Yes, Steam might want to automatically update Fallout 4 whenever Bethesda pushed out something new, but you can choose to hit [[[Pause]]](https://youtube.com/shorts/SbTS0UDKAvU?si=mgFtvo5BP8dUIqRp).
And you can make a second (or third, or fourth!) copy of Fallout 4.

Why? So there's three common reasons vaulties want a separate copy of Fallout 4:

### Mod compatibility

Some mods only work on the older version of the game (OG), before the next-gen update (NG) or the Anniversary Edition (AE). Steam always installs the latest version (AE) and updating breaks some OG mods, while downgrading means missing out on the latest mods and access to the in-game Creations menu.

### Save game safety

Updates can break existing saves. A separate copy means you can test a new update on a fresh install first, without risking a save you've spent hours building your settlement in.

### Running multiple Wabbajack modlists

Different [Wabbajack modlists](https://www.wabbajack.org/gallery?game=fallout4) need different game versions and each deserves its own clean install to avoid conflicts. A separate copy per Wabbajack modlist means you can run several at once without them fighting over the same files.

How? Get the best of all worlds with a fully separate copy of Fallout 4. Each copy stays locked to whichever version and modlist you decide. And you're free to update, downgrade, or experiment on any single copy without risking the others.

**YOU'RE PREPARED FOR THE FUTURE!**

---

## Quick walkthrough

1. Find and copy your Fallout 4 folder
2. Check the game version (optional but highly recommended)
3. Download the matching F4SE build (optional but highly recommended)
4. Install F4SE into the copy (optional but highly recommended)
5. Confirm the copy launches
6. Download and install MO2 as a portable instance
7. Point MO2 at the copy, enable local save games (and game settings)
8. Verify paths and launch through MO2

**Reward**: a clean, independent Fallout 4 copy

**Leads to**: upgrading, downgrading, or installing a Wabbajack modlist

---

## Detailed Walkthrough

### Part 1: Copy the game

#### Locate your Fallout 4 folder

Right-click Fallout 4 in Steam Library, choose **Manage**, then **Browse local files**. Or check manually at `C:\Program Files (x86)\Steam\steamapps\common\Fallout 4`, adjusted for your drive. **Note**: Steam Settings, then Storage, lists all library folders if you're unsure which one.

#### Copy that folder

Copy your Fallout 4 folder to a new location, for example: `C:\Games\Fallout4_Copy`.

#### Check your Fallout 4 version

Right-click `Fallout4.exe`, Properties, Details tab, check File version. Or in-game, bottom left of the Settings menu. There are three main game versions to be aware of:

1. `1.10.163` - OG, the long-stable pre-2024 version.
2. `1.10.984` - NG, the April 2024 Next-Gen update.
3. `1.11.1xx` - AE, the November 2025 Anniversary Edition version edition you'd get from Steam today.

#### Download the matching F4SE build (optional but highly recommended)

Current version is at [f4se.silverlock.org](https://f4se.silverlock.org) covers AE and NG. Archived versions, needed for OG `1.10.163`, is at [f4se.silverlock.org/archive](https://f4se.silverlock.org/archive). Match the build to the exact tier you checked above, an AE build won't run on an OG copy and vice versa. **Note**: Recommended to give you complete control over the game launch. If Steam decides you need an update, F4SE let's you completely bypass that.

#### Install F4SE into the copy

Extract into your new folder, for example, `C:\Games\Fallout4_Copy\Fallout4\`, alongside `Fallout4.exe`. **Note**: Skip this step if you already have F4SE installed.

#### Confirm the game runs

Launch `Fallout4.exe` preferably using the F4SE launcher: `f4se_loader.exe` directly. **Note**: Keep Steam running in the background, `steam_api64.dll` needs an active session even for a direct launch.

#### Note on shared data

This second copy of Fallout 4 still reads and writes to `Documents\My Games\Fallout4`. Existing saves and INIs will show up here until MO2 redirects them. No sweat, this behaviour is expected at this stage.

---

### Part 2: Set up portable MO2

#### Download MO2

From the Assets section in [Mod Organizer 2 GitHub releases](https://github.com/Modorganizer2/modorganizer/releases) page.

#### Install as a portable instance

Point the installer at a folder of your choice, I use the same parent folder, for example: `C:\Games\Fallout4_Copy\MO2`. Choose Portable instance when MO2 asks Global or Portable on first launch.

#### Point MO2 at your game copy

Browse to your Fallout 4 copy, for example: `C:\Games\Fallout4_Copy\Fallout4\` as the managed game folder.

#### Enable separate saves (and game settings)

Tick profile-specific save games and INI files on the profile settings screen. This keeps your save files and game settings completely seperate.

#### Verify paths

Open `ModOrganizer.ini` inside the MO2 folder, confirm paths point to the new copy. Check Modify Executables in MO2 for the F4SE loader as double check.

#### Launch and confirm clean state

Launch via MO2. Confirm old saves don't appear.

---

## Stages

| Stage | Status | Description |
| --- | --- | --- |
| 10 | ☐ | Find Fallout 4 install folder |
| 20 | ☐ | Copy folder to new location |
| 30 | ☐ | Check game version |
| 40 | ☐ | Download matching F4SE build |
| 50 | ☐ | Install F4SE into copy |
| 60 | ☐ | Confirm copy launches standalone |
| 70 | ☐ | Download MO2 |
| 80 | ☐ | Install MO2 as portable instance |
| 90 | ☐ | Point MO2 at the copy |
| 100 | ☐ | Enable Local Savegames (and game settings) |
| 110 | ☐ | Verify ModOrganizer.ini paths and executables |
| 120 | ✅ | Copy confirmed clean, ready for mods |

---

## Notes

> **Payoff**
> The Fallout 4 copy launches first try, no version mismatch errors.
> **Action**
> Match the F4SE build to your exact game version before installing anything. There are three main versions now: OG, NG, and AE.

> **Payoff**
> This Fallout 4 copy becomes a truly independent game, script extender and all, not just a folder with the same files in it.
> **Action**
> Install F4SE. Optional, but recommended, this is the step that actually separates the two copies rather than just duplicating them.

> **Payoff**
> The Fallout 4 game launches even outside Steam's own launcher.
> **Action**
> Keep the Steam client open in the background, even for direct exe launches.

> **Payoff**
> The new Fallout 4 copy stays genuinely clean, no old saves sneaking in.
> **Action**
> Tick profile-specific save games in MO2's profile settings, don't rely on a different in-game profile alone.

---

## Resources

[Embedded Webpage: Mod Managers and Downgrade Tools](https://viabledahlia.raindrop.page/mod-managers-and-downgrade-tools-74272451/embed)

---

## Related pages

* [Commonwealth Tools](https://viabledahlia.github.io/commonwealth-tools/)
