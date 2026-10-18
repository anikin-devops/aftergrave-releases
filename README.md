# Aftergrave Launcher

Aftergrave Launcher installs and updates games for Windows and macOS. It
downloads only what changed since your installed version, checks every file
before it is used, repairs damaged installations, and starts the game.

Games available through Aftergrave:

- **HPTCG: Arena** — a free, fan-made digital adaptation of the Harry Potter
  Trading Card Game ([hptcg-arena.com](https://hptcg-arena.com)).

## Download

**No launcher release is available yet.** Builds will appear under
[Releases](https://github.com/anikin-devops/aftergrave-releases/releases).
Until then, HPTCG: Arena is installed from
[its own download page](https://github.com/anikin-devops/hptcg-arena).

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

The launcher is not signed with a commercial code-signing certificate and is not
notarized by Apple. On first launch:

- **Windows** may show a SmartScreen prompt; choose **More info → Run anyway**.
- **macOS** blocks the first launch; open **System Settings → Privacy & Security**
  and choose **Open Anyway** for Aftergrave Launcher.

Download the launcher only from this repository.

## Support

Report problems through the game's community channels listed on
[hptcg-arena.com](https://hptcg-arena.com).
