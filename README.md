# Vietnam War multiplayer mod — experimental binary

> **WARNING: UNTESTED MULTIPLAYER BUILD.** This mod is experimental and is **not guaranteed to work well, or to work at all**. It may crash, desynchronize, or behave incorrectly. Back up your saves before trying it. Do not rely on it for a campaign you cannot afford to lose.

The only mod file in this repository is `Mods/VietnamMPTransportProbe.dll`. It requires a separate installation of MelonLoader for the IL2CPP version of *Vietnam War*; neither the game nor MelonLoader is redistributed here.

This binary is pinned to Steam game build **25826276**. Both players need that exact game build and the same mod DLL. Put the DLL in each player's `VietnamWar/Mods` folder. The host presses **F10** to create a private Steam lobby and **F11** to open Steam's invite dialog. The other player accepts the Steam invite.

**What was actually checked (October 11, 2026):** the game launched on one PC, the mod passed its build fingerprint check, and Steam reported a private lobby ready with authentication and relay available. **No remote player joined this build.** Joining, gameplay synchronization, long-session stability, and save behavior remain untested. A successful local host does not establish that multiplayer works.

Mod version: **0.4.11**. DLL SHA-256: `DEA6AE9EFDB312E9BAB02FAA66413266BF08B43FC6B20F3D3DF4285CEC1DCEBC`.
