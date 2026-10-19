<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/aftergrave-games-white-logo.png">
    <img src="assets/aftergrave-games-black-logo.png" alt="Aftergrave Games" width="320">
  </picture>
</p>

# Aftergrave Launcher

Aftergrave Launcher installs and updates games for Windows and macOS. It
downloads only what changed since your installed version, checks every file
before it is used, repairs damaged installations, and starts the game.

Games available through Aftergrave:

- **HPTCG: Arena** — a free, fan-made digital adaptation of the Harry Potter
  Trading Card Game ([hptcg-arena.com](https://hptcg-arena.com)).

## Download

🪟 **[Download Aftergrave Launcher for Windows](https://github.com/anikin-devops/aftergrave-releases/releases/latest/download/AftergraveLauncher.exe)**
Windows 10/11, 64-bit. A single file: run it, pick where to install the game,
press **Install**.

🍏 **[Download Aftergrave Launcher for macOS](https://github.com/anikin-devops/aftergrave-releases/releases/latest/download/AftergraveLauncher-macOS.zip)**
macOS 12.0 or later, Apple silicon and Intel. Extract the ZIP and move
`Aftergrave Launcher.app` to Applications; follow the first-launch steps below.

All versions are under
[Releases](https://github.com/anikin-devops/aftergrave-releases/releases).
A running launcher tells you when a newer launcher is available.

## How updates work

- Each game release is split into small pieces. When a new version comes out, the
  launcher downloads only the pieces you do not already have, so most updates are
  a fraction of the full game.
- Every update is signed by the game's publisher. The launcher installs nothing
  whose signature or checksum does not match.
- An interrupted update continues where it stopped the next time you open the
  launcher.
- **Repair** checks every game file and downloads only what is missing or damaged.

## Security notes

The launcher is not yet signed by Microsoft or notarized by Apple (that needs paid
developer accounts), so the system asks once per downloaded version:

- **Windows:** SmartScreen → **More info → Run anyway**.
- **macOS 15 and later:** open the app once and close the warning, then
  **System Settings → Privacy & Security → Open Anyway** and enter your password.
  The button stays there for about an hour after the blocked launch.
- **macOS 12–14:** right-click the app → **Open** → **Open**.

Download the launcher only from this repository, and never disable Gatekeeper.

## Support

Report problems through the game's community channels listed on
[hptcg-arena.com](https://hptcg-arena.com).
