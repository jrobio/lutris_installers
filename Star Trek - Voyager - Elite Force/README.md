# Star Trek: Voyager - Elite Force

This script installs **Star Trek: Voyager Elite Force** mods on top of an 
already installed instance through Wine.

- Please report issues to the lutris_installer repo: 
https://github.com/jrobio/lutris_installers

## Wine Install Notes

- This installer expects a installed version of 
**Star Trek: Voyager - Elite Force** registered in Lutris.

## Versions

### Graphics Overhaul Project Mod

- Expects a rar archive of 
[don_quichote's](https://www.moddb.com/members/don-quichote) mod: 
[Graphic Overhaul Project](https://www.moddb.com/mods/elite-force-graphic-overhaul-project).
- Expects the Expansion to be installed (the 
[GOG](https://www.gog.com/en/game/star_trek_voyager_elite_force) version of 
the game has this included in its installer).
- **Star Trek: Voyager - Elite Force** should be launched at least once before 
using this installer.
- The installer alters `autoexec.cfg` to the desktop resolution and sets 
English as the default language.

#### Known Issues

- Known issues 
[ModDB Forum post](https://www.moddb.com/mods/elite-force-graphic-overhaul-project/forum/thread/known-bugs-and-issues-v090)
- `Quake3.exe` has been set as the main file. However, if you experience 
[performance issues](https://www.moddb.com/mods/elite-force-graphic-overhaul-project/forum/thread/mod-installation-v090-and-configuration),
you may wish to change that to `stvoy_GOP_SP.exe`.
- Installation of this mod is not recommended on systems with displays smaller 
than 1920x1080 (ex. Valve's Steam Deck). That said, it works well in the Steam 
Deck's desktop mode, should you have a docked monitor resolution of 1920x1080 
or greater. 

## Acknowledgements

- Mod author [don_quichote](https://www.moddb.com/members/don-quichote) for 
the [Graphic Overhaul Project mod](https://www.moddb.com/mods/elite-force-graphic-overhaul-project).
- [Good Old Games](https://www.gog.com/en/game/star_trek_voyager_elite_force): 
Figuring out the rights on old games ain't easy, it is appreciated.
- [Raven Software](https://www.ravensoftware.com/): Star Trek Quake - what a 
concept!
- Lutris user robertosanchez: Thank you for providing the base Star Trek: 
Voyager - Elite Force 
[installer]((https://lutris.net/games/install/29545/view)) for GOG.
- [Trek Core](https://gaming.trekcore.com/eliteforce/): for maintaining 
accurate and obscure information as well as media about all things Star Trek.
