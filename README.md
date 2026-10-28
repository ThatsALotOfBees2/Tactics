# Realblast Siege

A tactical breach-and-defend shooter where everything breaks: 5v5 against bots or with friends.
Prototype build for Windows 10/11 and Ubuntu (64-bit).

## Install

Open **[Releases](https://github.com/ThatsALotOfBees2/Tactics/releases/latest)** and download
the file for your system.

**Windows:** `RealblastSiege-<version>-win64.zip`
1. Unpack it anywhere (keep the `RealblastSiege` folder together).
2. Run `RealblastSiege.exe`.

**Ubuntu** (22.04 or newer, also Debian, Mint, Pop!_OS): `realblast-siege_<version>_amd64.deb`
1. Double-click the file and press **Install**, or in a terminal:
   `sudo apt install ./realblast-siege_<version>_amd64.deb`
2. Start **Realblast Siege** from the app menu, or run `realblast-siege`.

To remove it: `sudo apt remove realblast-siege`.

The launcher checks for a newer version every time it starts, downloads it when there is one,
and then starts the game. No reinstalling needed (on Ubuntu the updates go to
`~/.local/share/realblast-siege`).

## Play together

Main menu → **MULTIPLAYER**: host a game, or join one from the server list (or by the host's
address). Players pick attackers or defenders in the lobby; bots fill the empty slots.

Hosting: the game opens UDP port **24565** on your router by itself when the router allows it
(UPnP). If friends can't join, forward UDP 24565 to your PC. Allow the game through Windows
Firewall when asked.

## Controls

WASD move, Shift sprint, C crouch, Z prone, Q/E lean, Space vault, Left mouse fire, Right mouse
aim, R reload, F interact / reinforce / barricade, V melee, 1–2 weapons, 3–4 gadgets,
G quick gadget, 5 drone / cameras, Tab scores, Esc pause.
