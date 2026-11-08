# Realblast Siege

> **v0.2.7: real sounds, smarter bots, drone boost.** Recorded sounds, bots that learn from their games and no longer get stuck on ladders, a drone boost and higher hop, falling off the map kills, plus Haneul Tower and the map editor from v0.2.6.
> New players on Windows: grab **RealblastLauncher.exe**
> from the [latest release](https://github.com/ThatsALotOfBees2/Tactics/releases/latest), put it in
> an empty folder and open it: it installs, updates and starts the game. Everyone in a game needs
> the same version.

A tactical breach-and-defend shooter where everything breaks: 5v5 against bots or with friends.
Prototype build for Windows 10/11 and Linux (64-bit).

## Install

Open **[Releases](https://github.com/ThatsALotOfBees2/Tactics/releases/latest)** and download
the file for your system.

**Windows, easiest:** `RealblastLauncher.exe`
1. Put it in an empty folder and open it (if Windows warns about an unknown app: **More info → Run anyway**).
2. Press **INSTALL**, then **PLAY**. Open it again any time: it updates the game first.

**Windows, by hand:** `RealblastSiege-<version>-win64.zip`
1. Unpack it anywhere (keep the `RealblastSiege` folder together).
2. Run `RealblastSiege/RealblastSiege.exe`.

**Linux** (Ubuntu 22.04 or newer, Debian, Mint, Pop!_OS and others): `RealblastSiege-<version>-linux.zip`
1. Unpack it anywhere (keep the `RealblastSiege` folder together).
2. Run `RealblastSiege/RealblastSiege.x86_64` (if your file manager unpacked it without the run
   permission: `chmod +x RealblastSiege.x86_64`).

**Have the launcher from an older version** (Windows, or the Ubuntu .deb)? Just open it. It checks
for a newer version every time it starts, downloads it, and then starts the game.

## Play together

Main menu → **MULTIPLAYER**.

- **Host:** type a game name and press **HOST**. The game shows up in everyone's game list. Allow
  it through Windows Firewall if it asks.
- **Join:** pick a game from the list and press **JOIN**. No addresses, no port forwarding, no accounts.

Players pick attackers or defenders in the lobby; bots fill the empty slots.

Players connect straight to each other: the games open a way through both routers by themselves.
A few connections can't be joined this way (very strict routers, some mobile hotspots and carrier
networks). If a join fails, let the other player host. Or everyone joins a free virtual LAN
(Tailscale, ZeroTier) and uses **join by address**.

## Controls

WASD move, Shift sprint, C crouch, Z prone, Q/E lean, Space vault, Left mouse fire, Right mouse
aim, R reload, F interact / reinforce / barricade / pick up, V melee, 1–2 weapons, 3–4 gadgets,
5 drone / cameras, X scan (hold), Tab scores, Esc menu. Keys can be changed in Settings.
