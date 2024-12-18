# ahud adjustments
This is an ahud fork, meaning the project is copied from the [original ahud repo](https://github.com/n0kk/ahud), and then I have added changes that I want.

### Complete list of changes and their justifications in this fork:
- Vertically centered the "Play" button on the main menu
  - I thought it looked weird for the "Play" text to have its bottom aligned with the bottom of the TF logo to its left
  - In this version, the "Play" text is centrally aligned around the same axis as the TF logo
- Fixed MVM currency label being invisible
  - In the official ahud, the mvm currency label is stuffed into the top left corner and only about 1/8th if it is visible
  - In this version, the currency label is whole and is placed above the player's health

Below is the readme from the original ahud project by [n0kk](https://github.com/n0kk).

# ahud

A custom HUD for Team Fortress 2.  
Original concept by [kyle](https://github.com/hikyle).

#### Features

* Custom colors
* Custom crosshairs
* 6v6 scoreboard
* Alternative styles
* Home Server button
* 16:9, 16:10, and 4:3 support
* Matchmaking and MvM support

#### Screenshots

* [Main Menu](https://i.imgur.com/Kx70I3P.jpg)
* [Buffed HP](https://i.imgur.com/WgR6jeE.jpg)
* [Low HP & Ammo](https://i.imgur.com/AV3mNzm.jpg)
* [Alt. Buffed HP](https://i.imgur.com/BKmdCnp.jpg)
* [Alt. Low HP & Ammo](https://i.imgur.com/m4gILKr.jpg)
* [Default scoreboard](https://i.imgur.com/cigUnUo.jpg)
* [6v6 scoreboard](https://i.imgur.com/xya3Hkg.jpg)

More screenshots: [Imgur album](http://imgur.com/a/569GH)

## Installation

1. Download ahud by clicking `Download ZIP` from the green `Code` button on the ahud GitHub repo.
2. Navigate to  `..\Steam\steamapps\common\Team Fortress 2\tf\custom`.
3. Extract `ahud-master` from the ZIP file to the `custom` folder.
4. Verify `materials`, `resource`, `scripts`, and `info.vdf` are inside the `ahud-master` folder.
5. Run Team Fortress 2.

For thorough instructions on installing a HUD for TF2, check out the [HUDS.TF guide](https://huds.tf/forum/showthread.php?tid=1987).  
A third-party installer, [ainstaller](https://github.com/ainstaller/aInstaller/releases), is also available.

## Customization

Refer to the [Wiki](https://github.com/n0kk/ahud/wiki/Customization).

## Support
[Report bugs here](https://github.com/n0kk/ahud/issues)

**Windows**: Yes
* 4:3 - 1024×768 and above  
* 16:9 - 1280x720 and above  
* 16:10 -  1280x800 and above  

**Linux**: No  
**Mac**: No

I have tested ahud on my Windows PC using a 16:9 monitor primarily on resolutions 1280x720 and above. ahud works on 16:10 and 4:3 and I'll be providing support for these aspect ratios as best as I can. Unfortunately, no Mac or Linux support.