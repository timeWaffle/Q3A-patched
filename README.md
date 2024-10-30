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
**Waffles-Canned-Q3A-macOS-arm-v1.02.zip**  
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
### v2.1-UPGRADE
+ THE UPGRADE PACK INCLUDES ONLY THE UPDATED PAKS. YOU MUST MOVE THEM INTO YOUR EXISTING Q3A INSTALLATION.
+ Excessive Plus 2.3 Mod ('excessiveplus' directory) [[www.excessiveplus.net]]
+ BFG Edition 1.0 (pak9.pk3) [[www.moddb.com/mods/quake-iii-arena-bfg-edition]]
+ BFG Edition enhances nearly every aspect of the game.
+ Created Waffles-Quake3Arena-Upgrade(MultiPlatform)v2.1.rar to distribute BFG Pack, Excessive Plus, and Models ONLY.
  
- Github Does not like release file sizes over 2GB. Will need to break up future Canned versions into upgrade packs.


### UPGRADE INSTRUCTIONS:

### BFG Edition Upgrade:
1. Copy pak8a.pk3 and pak9.pk3, add to your existing Quake 3 Arena installation \baseq3 folder:

2. Your installation directory may vary depending on platform.
+ Windows: `C:\Program Files\Quake 3 Arena\baseq3\.`
+ Mac: `/Applications/Quake 3 Arena/baseq3/.`
+ Linux: `/opt/quake3/baseq3/.`

3. Copy the "autoexec.cfg" file (necessary to set key parameters and apply an optimal configuration) into your q3a config directory:

4. Your config directory may vary depending on platform.
  + Windows: `C:\Users\%USERNAME%\AppData\Roaming\Quake3\baseq3\.`
  + Mac: `~/Users/%userName%/Library/Application Support/Quake 3 Arena/baseq3/.`
  + Linux: `~/.q3a/baseq3/.`

6. Done!

### Excessive Plus+ Upgrade:
1. Copy the entire included 'excessiveplus' directory to your existing install of Quake 3 Arena.

2. Your installation directory may vary depending on platform.
  + For Windows: `C:\Program Files\Quake 3 Arena\.`
  + For Mac: `/Applications/Quake 3 Arena/.`
  + For Linux: `/opt/quake3/.`

4. The 'excessiveplus' directory lives in the same directory as baseq3.

6. Done!

Please see the example directory hierarchy below for reference:
```
$my_install_dir/Quake3/
	|
	├── baseq3
	│   ├── pak0.pk3
	│   ├── pak1.pk3
	│   ├── pak2.pk3
	│   ├── pak3.pk3
	│   ├── pak4.pk3  
	│   ├── pak5.pk3
	│   ├── pak6.pk3
	│   ├── pak7.pk3
	│   ├── pak8.pk3
	│   ├── pak8a.pk3 -- Waffles Upgrade Pack 
	│   ├── pak9.pk3  -- Waffles Upgrade Pack 
	│   ├── qwpak0.pk3
	│   ├── qwpak1.pk3
	│   ├── qwpak2.pk3
	│   ├── qwpak3.pk3
	│   └── qwpak4.pk3
	|
	├── excessiveplus -- Waffles Upgrade Pack
	│   ├── z-xp-2_0a.pk3
	│   ├── z-xp-2_1.pk3
	│   ├── z-xp-2_2b.pk3
	│   ├── z-xp-2_3.pk3
	│   ├── zzzz-md3-gp01.pk3
	│   ├── zzzz-md3-gp01fb.pk3
	│   ├── zzzz-md3-Sonic.pk3
	|   └── zzzz-skn-grunt-mlpb.pk3

```

Special thank you to Briston-idtech89 for this BFG Edition!
[[https://www.moddb.com/mods/quake-iii-arena-bfg-edition]]

Special thank you to the Excessive Plus+ Community!
[[www.excessiveplus.net]]


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
