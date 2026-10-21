# NCAA Football 06 — XBE Recomp

Unofficial native Windows recompilation of the original Xbox version of NCAA Football 06. Public beta; original game files required.

Built using [XboxXBERecomp](https://github.com/TGP482/XboxXBERecomp) by [TGP482](https://github.com/TGP482).

## Public Beta

Gameplay, menus, controller navigation, and audio have been tested. Dynasty simulation has been tested across several seasons, and Race for the Heisman has been tested through entry into the tryout. Bugs may remain, and compatibility with all hardware and game modes is not guaranteed.

Further development and ongoing support are not currently planned. Community forks and improvements are welcome under the included licenses.

## Installation

This project does not include game files. You must provide files from your own legally acquired original Xbox copy of NCAA Football 06.

1. Download the playable package from [Releases](../../releases).
2. Extract the entire archive to a writable folder.
3. Place your extracted Xbox game files in the `assets` folder, with `default.xbe` directly inside it alongside `DATA` and all remaining game files and folders.
4. Run `NCAA06.exe`.

Keep the supplied DLLs and settings file beside the executable. PlayStation 2 game files are not compatible.

This build targets `default.xbe` with SHA-1 `8013b94db9bad5bee7b0529d6648a93987961532`. Other Xbox revisions are unverified.

## Settings

Close the game before editing `ncaa06-settings.toml`.

- Adjustable output resolution and render scale.
- Windowed and borderless display modes.
- Anisotropic filtering.
- Alt+Enter or F11 toggles windowed/borderless mode.
- Keep `xbox_720p = false` for the tested configuration. Higher PC output resolutions can still be selected using `width` and `height`.
- Save data is stored in `UDATA` on the emulated Xbox E: drive, inside the local `hdd` folder. Back up your `hdd` folder before upgrading.
- If performance is poor, try `render_percent = 100`.

## Source

The separately attached Source-Build package is for users who want to modify or rebuild the project. Follow its included build instructions.

Download `NCAA06-Source-Build_Package.zip` from Releases for the complete build package. GitHub's automatically generated **Source code** archives contain the repository files and may not include that package's contents.

Keep all applicable license and third-party notices when redistributing.

This is an unofficial community project and is not affiliated with or endorsed by EA, the NCAA, or Microsoft.
