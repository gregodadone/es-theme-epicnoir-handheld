# EpicNoir Theme for Handheld Devices with 4:3 Displays

Based on the EpicNoir theme adapted by [CodyV59](https://github.com/CodyV59).

This theme supports multiple languages. **English and Spanish are currently available, with English as the default language.** It also includes XML fixes and completed artwork resources.

The theme is intended for any handheld device with a 4:3 display running a compatible version of EmulationStation, including the variants used by ArkOS and Batocera. The included systems are listed below; theme support for a system does not guarantee that your device can emulate all its games.

## License

This work is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png "Creative Commons License")

You may:

- Share and copy the theme.
- Edit, adapt and modify it.

You must:

- Credit the creators.
- Indicate changes made to the theme.
- Distribute adaptations under the same license.

Commercial use is prohibited.

## Note

By downloading and installing this theme, you are assumed to hold the rights to all ROMs you intend to use. This is a free theme that you may install and share with others, but **you may not sell it or use it for commercial purposes.** See the License section above for details.

## Acknowledgments and Credits

The artwork belongs to the artists who contributed their talent and time to create it. Much of their work can be found on [DeviantArt](http://www.deviantart.com/).

## Features

- A clean, dark interface.
- Multiple-language support, currently including English and Spanish.
- Backgrounds and controller images for every included system; some resources are shared across systems and collections.
- Custom collections for game genres such as Action, Adventure and Platformers.
- Support for All Games, Favorites, Last Played and Custom Collection.
- Support for screenshots, box art and videos.

## Installation and Updates

1. Close EmulationStation.
2. Download a copy of this theme into the themes directory used by your installation of EmulationStation.
3. Start EmulationStation and select the theme in it's user interface settings.

The themes directory depends on your operating system and configuration. Use the directory configured for your ArkOS or Batocera installation.

### Updating

Close EmulationStation before updating. Replace the theme files with the updated version, then restart EmulationStation. If you installed the theme as a Git checkout, run `git pull` from that checkout instead.

## Theme Notes

This theme supports video. You can scrape images alongside videos. If both are available, selecting a game displays its image for 1.4 seconds before transitioning to the video.

Game screenshots are not included with the theme. You can obtain them using a scraper.

### Languages

The theme supports multiple languages and currently provides **English and Spanish**. English is the default and fallback language. When EmulationStation is set to Spanish, the theme displays its Spanish translations. For any language without a specific translation, theme text remains in English.

On ArkOS and Batocera, choose Spanish in the application language settings to display the theme in Spanish. A separate theme installation is not required.

Translations are defined in each XML file: the unfiltered English text appears first, followed by its Spanish translation with `lang="es"`. Images and layout are shared across languages. Console and manufacturer names usually remain unchanged. This feature does not translate game descriptions obtained from a scraper.

System descriptions, genres, collections and theme options are available in both languages. The table below lists the English names displayed by default.

### Included Systems, Genres and Collections

This list reflects the folders in this distribution. Each entry includes an XML file, a background and a controller image. Identifiers are the folder names EmulationStation uses to select the system theme.

| Identifier | Name in the Theme |
| --- | --- |
| `3do` | 3DO |
| `action` | Action Games |
| `adventure` | Adventure Games |
| `amiga` | Amiga |
| `amigacd32` | Amiga CD32 |
| `amstradcpc` | Amstrad CPC |
| `arcade` | Arcade |
| `atari2600` | Atari 2600 |
| `atari5200` | Atari 5200 |
| `atari7800` | Atari 7800 |
| `atari800` | Atari 800 |
| `atarijaguar` | Atari Jaguar |
| `atarilynx` | Atari Lynx |
| `atarist` | Atari ST |
| `atomiswave` | Atomiswave |
| `auto-allgames` | All Games |
| `auto-favorites` | Favorite Games |
| `auto-lastplayed` | Last Played |
| `btmups` | Beat 'em Up Games |
| `c128` | Commodore 128 |
| `c16` | Commodore 16 |
| `c64` | Commodore 64 |
| `colecovision` | ColecoVision |
| `cps1` | Capcom CPS-1 |
| `cps2` | Capcom CPS-2 |
| `cps3` | Capcom CPS-3 |
| `custom-collections` | Custom Collection |
| `daphne` | Daphne |
| `doom` | Doom |
| `dos` | Microsoft MS-DOS |
| `dreamcast` | Sega Dreamcast |
| `easyrpg` | Easy RPG |
| `ecwolf` | Wolfenstein |
| `famicom` | Famicom Disk System |
| `fbn` | FinalBurn Neo |
| `fbneo` | FinalBurn Neo |
| `fds` | Famicom Disk System |
| `fighting` | Fighting Games |
| `gameandwatch` | Game & Watch |
| `gamegear` | Sega GameGear |
| `gb` | Nintendo Game Boy |
| `gba` | Game Boy Advance |
| `gbah` | GBA Hacks |
| `gbc` | Game Boy Color |
| `gbch` | GBC Hacks |
| `gbh` | Game Boy Hacks |
| `gc` | Nintendo GameCube |
| `genesis` | Sega Genesis |
| `genh` | Sega Megadrive Hacks |
| `ggh` | Game Gear Hacks |
| `imageviewer` | Screenshots |
| `intellivision` | Intellivision |
| `j2me` | J2ME |
| `mame` | MAME |
| `mastersystem` | Sega Master System |
| `mega32x` | Sega Mega 32x |
| `megacd` | Sega Mega-CD |
| `megadrive` | Sega Megadrive |
| `megadrive-japan` | Mega Drive Japan |
| `megaduck` | Mega Duck WG-108 |
| `mplayer` | Mplayer |
| `msx` | MSX |
| `msx2` | MSX2 |
| `n64` | Nintendo 64 |
| `naomi` | Sega Naomi |
| `nds` | Nintendo DS |
| `neogeo` | Neo-Geo |
| `neogeocd` | Neo-Geo CD |
| `nes` | Nintendo NES |
| `nesh` | Nintendo NES Hacks |
| `ngp` | Neo Geo Pocket |
| `ngpc` | Neo Geo Pocket Color |
| `odyssey2` | Odyssey 2 |
| `openbor` | Openbor |
| `pc` | Microsoft MS-DOS |
| `pc98` | NEC PC-98 |
| `pce-cd` | PC Engine CD |
| `pcengine` | PC Engine |
| `pcenginecd` | PC Engine CD |
| `pcfx` | PC-FX |
| `pico-8` | PICO 8 |
| `platformers` | Platform Games |
| `pokemini` | Pokémon Mini |
| `ports` | Ports |
| `power` | Shutdown |
| `psp` | Sony PSP |
| `pspminis` | Sony PSP |
| `psx` | Sony Playstation |
| `racing` | Racing Games |
| `residualvm` | ResidualVM |
| `retroarch` | Options |
| `retropie` | Options |
| `rpgs` | Role-Playing Games |
| `satellaview` | Satellaview SNES |
| `saturn` | Sega Saturn |
| `sc-3000` | Sega SC-3000 |
| `scummvm` | ScummVM |
| `sega32x` | Sega Genesis 32x |
| `segacd` | Sega Mega-CD |
| `sfc` | Super Famicom |
| `sg-1000` | Sega SG-1000 |
| `snes` | Super Nintendo |
| `snesh` | Super Nintendo |
| `snesmsu1` | Super Nintendo |
| `solarus` | Solarus |
| `sufami` | SNES Sufami Turbo |
| `supergrafx` | SuperGrafx |
| `supervision` | Supervision |
| `tg16` | TurboGrafx-16 |
| `tg16cd` | TurboGrafx-CD |
| `ti99` | Texas TI-99 |
| `tic-80` | TIC-80 |
| `tools` | Tools |
| `turbografx` | TurboGrafx-16 |
| `turbografxcd` | TurboGrafx-CD |
| `uzebox` | UZEBOX |
| `vectrex` | Vectrex |
| `vic20` | COMMODORE VIC-20 |
| `videopac` | Videopac G7000 |
| `virtualboy` | Nintendo Virtual Boy |
| `wonderswan` | Wonderswan |
| `wonderswancolor` | Wonderswan Color |
| `x68000` | X68000 |
| `zx81` | SINCLAIR ZX-81 |
| `zxspectrum` | Sinclair ZX Spectrum |
