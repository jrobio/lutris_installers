# Star Trek: Starfleet Command II - Empires at War

This script installs **Star Trek: Starfleet Command II - Empires at War**, the
Sulu bonus missions, patches it to the latest official version (v2036), and 
adds the Hot and Spicy Forums community patch v2037.

- Expects the cdrom version of the game
- Expects a zip archive of 
[Starfleet_2037](https://hotandspicyforums.com/sfc2-empires-at-war-patch-2-037-t20068.html)
- Please report issues to the lutris_installer repo: 
https://github.com/jrobio/lutris_installers

## Wine Install Notes
- `Forfeit` the Taldren upsell messages. They will provide an option to turn
this off by entering `123` launching the game twice after installation.
- Do not install `directx 7`.
- `Exit` the notepads spawned by the patch installation process to continue
installation.
- Installation of the patches may hang for a few seconds after completion, 
this is expected.
- Installer will prompt user for desired resolution from supported options, 
including:
    - `640x480`
    - `800x600`
    - `1280x720`
    - `1360x768`
    - `1366x768`
    - `1600x900`
    - `1920x1080`
- The installer Requires `perl`, but most linux distributions should have this 
as a default package.
- `Exit` the installer, rather than launch the game, on completion.

## Known Issues

- The tutorials do not work...sorry.

## Acknowledgements

- [HotandSpicyForums](https://hotandspicyforums.com/sfc2-empires-at-war-patch-2-037-t20068.html)
and the users who put together the community patch.
- [Trek Core](https://gaming.trekcore.com/starfleetcommand2/index.html) for 
maintaining accurate and obscure information and media about all things Star 
Trek.
- Lutris community members [OJ1](https://forums.lutris.net/u/oj1/summary) and 
[legluondunet](https://forums.lutris.net/u/legluondunet/summary) for helping 
me troubleshoot this install script.
- [Archive.org](https://archive.org/) for helping to keep old and abandoned
software available.