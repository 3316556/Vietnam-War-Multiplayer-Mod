# Vietnam War multiplayer mod — experimental binary

> **WARNING: UNTESTED MULTIPLAYER BUILD.** This mod is experimental and is **not guaranteed to work well, or to work at all**. It may crash, desynchronize, or behave incorrectly. Back up your saves before trying it. Do not rely on it for a campaign you cannot afford to lose.

The only mod file in this repository is `Mods/VietnamMPTransportProbe.dll`. It requires a separate installation of MelonLoader for the IL2CPP version of *Vietnam War*; neither the game nor MelonLoader is redistributed here.

This binary is pinned to Steam game build **25826276**. Both players need that exact game build and the same mod DLL. Put the DLL in each player's `VietnamWar/Mods` folder. The host presses **F10** to create a private Steam lobby and **F11** to open Steam's invite dialog. The other player accepts the Steam invite.

**What was actually checked (October 11, 2026):** the game launched on one PC, the mod passed its build fingerprint check, and Steam reported a private lobby ready with authentication and relay available. A live host capture found 1,060 unique stronghold ownership entries and a readiness-safe ordnance catalog. **No remote player joined this build.** Joining, gameplay synchronization, long-session stability, and save behavior remain untested. A successful local host does not establish that multiplayer works.

Mod version: **0.4.12**. DLL SHA-256: `A6B69C5537EF56BD18571D9E99774850FDE872B187D50BBA59EEE88D01195155`.
