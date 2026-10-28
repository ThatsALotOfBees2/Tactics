# Realblast Siege

A tactical breach-and-defend shooter where everything breaks: 5v5 against bots or with friends.
Prototype build for Windows and Linux (64-bit).

## Install

1. Open **[Releases](https://github.com/ThatsALotOfBees2/Tactics/releases/latest)** and download
   `RealblastSiege-<version>-win64.zip` (Windows) or `RealblastSiege-<version>-linux.tar.gz` (Linux).
2. Unpack it anywhere (keep the `RealblastSiege` folder together).
3. Run `RealblastSiege.exe` (Windows) or `./RealblastSiege.x86_64` (Linux).

The launcher checks for a newer version every time it starts, downloads it when there is one,
and then starts the game. No reinstalling needed.

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
