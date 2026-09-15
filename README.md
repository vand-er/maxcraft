# MaxCraft

Modpacks for the Dragonland server. NeoForge 1.21.1, built around Cobblemon 1.8.1.

## Install

1. Install [MultiMC](https://multimc.org/) or [Prism Launcher](https://prismlauncher.org/).
2. Install **Java 21** and run the installer with its default options:

   ```
   https://dragonland.online/java.msi
   ```

   (That is Eclipse Temurin 21 for 64-bit Windows, straight from Adoptium. Prism can download Java by itself,
   MultiMC cannot, so do this first.)
3. **Add Instance** → **Import from zip**, and paste this link into the box:

   ```
   https://dragonland.online/pack.mrpack
   ```

4. Click **OK**. The launcher fetches the mods and sets the instance up for you (about 1 GB of downloads).
5. Select the instance → **Edit** → **Settings** → **Memory**, and set the maximum to **20480 MB**.
6. Same screen, **Java** tab: tick **Java installation**, click **Auto-detect** and choose the **21** entry.

   If you already had an old Java installed, the launcher will pick that one instead and the game will not start
   — the log says `Minecraft 24w14a and above require the use of Java 21`.
7. Close the launcher, then run the updater once. It checks the instance and switches on automatic updates, so
   every launch from then on picks up new mods by itself. It is already inside the instance you just made — right-click
   the instance → **Instance Folder** → `.minecraft` → double-click `maxcraft-sync.jar` — or download it:

   ```
   https://dragonland.online/sync.jar
   ```

   (It is a small Java program, not an installer, and the Java you installed in step 2 runs it. If the browser asks
   whether to keep the file, keep it. The same file is on the
   [Releases](https://github.com/vand-er/maxcraft/releases/latest) page as `MaxCraft-Sync.jar`.)

If your launcher refuses the pack file, use the full export instead — same pack, one 1 GB download, updater already
built in: `https://dragonland.online/pack.zip`

Both servers are already in the multiplayer list. The server is whitelisted, so ask for access before you join.

## What is in it

Cobblemon 1.8.1 and its add-ons, Create and Create Aeronautics, AE2, Sophisticated Storage and Backpacks,
Waystones, Farmer's Delight, Simple Voice Chat, a set of decoration mods, five shader packs, and the usual
performance and quality-of-life mods (Sodium, Iris, JEI, Jade, Xaero's).

Structures come from Cobblemon: Extra Structures, Cobblemon Trainer Structures, Aio's Extra Structures and Rad Gyms.
Loot chests are per-player (Lootr), so being second into a dungeon still gets you the loot, and FTB Ultimine breaks a
whole vein or tree at once when you hold the key.

There is an in-game quest book (press `` ` ``) that walks through every major mod and the Cobblemon trainer
battles, with loot-table rewards.

## Controls worth knowing

| Key | |
|---|---|
| `` ` `` | Quest book |
| `K` | Smartphone (heal party, PC, Pokédex) |
| `N` | Pokémon summary |
| `M` | Map |
| `J` | Waypoint |
| `G` | Start a fight with what you are looking at |
| `F6` | Toggle shaders |

## Updating

Nothing to do. The updater runs before every launch: it compares the instance with the newest release, fetches what
changed (usually a few mods, a few seconds) and the game starts. A jar you added yourself is switched off rather than
deleted, so the Mods tab can turn it back on.

If you skipped step 7, run `https://dragonland.online/sync.jar` once with the launcher closed and it takes over from
there. Re-importing the pack is never needed.
