```
             █ █ █▀█ █▀▀ █▀▀ █   █▀▀ ▀ █▀▀   █▀▀ █▀█ █▀█ █▀█ █▀▀ █▀▄
             █▄█ █▀█ █▀▀ █▀▀ █   █▀▀   ▀▀█   █   █▀█ █ █ █ █ █▀▀ █ █
             ▀ ▀ ▀ ▀ ▀   ▀   ▀▀▀ ▀▀▀   ▀▀▀   ▀▀▀ ▀ ▀ ▀ ▀ ▀ ▀ ▀▀▀ ▀▀ 
                 ▄▀▄ █ █ █▀█ █ █ █▀▀   ▀▀█   █▀█ █▀▄ █▀▀ █▀█ █▀█
                 █\█ █ █ █▀█ █▀▄ █▀▀    ▀▄   █▀█ █▀▄ █▀▀ █ █ █▀█
                  ▀\ ▀▀▀ ▀ ▀ ▀ ▀ ▀▀▀   ▀▀    ▀ ▀ ▀ ▀ ▀▀▀ ▀ ▀ ▀ ▀
```
# Welcome to the Arena!

This is a ready-to-run release of ioQuake3 for Windows for Quake 3 Frag Nights.

## MacOS(ARM) Package
**Waffles-Canned-Q3A-macOS-arm-v0.2.zip**  
Place unpacked ioQuake3 folder into `/Applications/`  
Run `ioquake3.app`

ioQuake3 will place configurations in:  
`/Users/userName/Library/Application Support/Quake3/baseq3/q3config.cfg`

ARM Macs should have no problem running full memory settings:  
`com_hunkMegs 1024; com_soundMegs 64; com_zoneMegs 128;`

## Windows Package
**Waffles-Canned-Quake3Arena(ioquake3)v1.zip**  
Unzip package. Place in your favorite directory.  
Double-click the shortcut **'Enter the Arena!'**

ioQuake3 configurations will be found:  
`C:\Users\User\AppData\Roaming\Quake3\baseq3\q3config.cfg`

Canned version ships with:  
`com_hunkMegs 512; com_soundMegs 32; com_zoneMegs 64`

# CHANGES:

## v2.0
- Updated to BFG Edition 1.0 (pak9.pk3)
  [[https://www.moddb.com/mods/quake-iii-arena-bfg-edition]]
- Created Waffles-Quake3Arena-UpgradePaksOnly(MultiPlatform)v2.rar to distribute BFG Pack and configurations only.
- Github Does not like release file sizes over 2GB. Will need to break up future Canned versions into upgrade packs.
- BFG Edition enhances nearly every aspect of the game.

### UPGRADE INSTRUCTIONS:

**Copy pak8a.pk3 and pak9.pk3, add them to your existing Quake 3 Arena installation \baseq3 folder:

`Windows: C:\Program Files\Quake 3 Arena\baseq3\.`

`MacOS: /Applications/Quake 3 Arena/baseq3/.`

```
.q3a/
├── baseq3
│   ├── pak0.pk3
│   ├── pak1.pk3
│   ├── pak2.pk3
│   ├── pak3.pk3
│   ├── pak4.pk3
│   ├── pak5.pk3
│   ├── pak6.pk3
│   ├── pak7.pk3
│   └── pak8.pk3
│   └── pak8a.pk3 --*
│   └── pak9.pk3  --*
│   └── qwpak0.pk3
│   └── qwpak1.pk3
│   └── qwpak2.pk3
│   └── qwpak3.pk3
│   └── qwpak4.pk3

*Waffles Quake 3 Arena Multiplatform LITE version includes the new pak8a.pk3 and pak9.pak necessary for BFG Edition.
```

**Copy the "autoexec.cfg" file (necessary to set key parameters and apply an optimal configuration) into:

`Windows ioquake3 Configurations: place it in C:\Users%USERNAME%\AppData\Roaming\Quake3\baseq3.`

`Mac ioquake3 Configurations: place it in /Users/userName/Library/Application\ Support\Quake3\baseq3`

Features:
- 178 Arenas: Includes both the original and Quake Live maps, with improvements to both.
- 227 Player Skins and 129 Bots: Exported models and sounds from Team Arena, as well as enhanced community skins, all maintaining the high quality of BFG. 
- Weapons: Updated using models from Quake Arena Arcade, with new skins, effects, and sounds, including ammunition boxes.
- Textures and Graphics: Almost 90% of graphics, or more, have been upscaled using AI, covering models, textures, effects, sprites, icons, and more.
- Sounds: New, high-quality sounds. Multiple sources.
- Hundreds of Minor Fixes: Too many to list individually.
- MULTIPLAYER compatible: All players must have the mod installed on the same version.

Special thank you to Briston-idtech89 for this compilation of improvements!

[[https://www.moddb.com/mods/quake-iii-arena-bfg-edition]]


## v.01 - v.02
- Initial Release
- Removed bloat mods
- Updated to latest ioQuake3 Release (Windows)
- Deployed v0.1 is Vanilla Q3A

---

## HOW DO I GET STARTED?:
1. Double-click the shortcut **'Enter the Arena!'**
2. Click **"Setup"** then **"Player"** to define your character model.
3. In **"Setup"**, you may also adjust **"Controls"**, **"System"**, and **"Game Options"** to your liking.

## HOW DO I JOIN A MATCH?:
1. Click **"Multiplayer"**
2. Hit **Space** to pause server searching.
3. Click **"Specify"** at the bottom left.
4. Enter the server address, default port `27960`.
5. Click **"FIGHT"** to enter the match.
