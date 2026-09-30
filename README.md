# ZC Ultimate Blaster Weapon Pack 1.0.0 (standalone)

**54 new blasters for STAR WARS Zero Company**, each a real weapon of its own in the Armoury, with its own model, name, icon, stats and
bolt colour. 39 come from Star Wars Battlefront II (2017) and 15 from Star Wars Jedi: Survivor.

The lightsabers are a separate mod, **ZC Complete Saber Weapon Pack** (coming later).

- Version 1.0.0, for game build 197649 (Steam).
- Author: Envian. Built with the Zero Company Mod SDK.

## What you get
Each blaster is a new MODEL on the Pistol, Rifle, Repeater or Longarm shelf, beside the game's own guns. It has its own meshes, eight
paint patterns on the body and barrel, its own numbers and bolt colour, and it takes the game's attachment modifications (drawn with the
gun's own Battlefront II pieces where it has them).

- **Pistols (12):** Bryar Pistol, SE-44, Blurrg-1120, DL-44, DH-17, SE-14C, RK-3, EC-17, DC-17, Glie-44, Relby-K23, Defender Sporting Blaster
- **Rifles (15):** DC-15A (BF2), DC-15S, DC-17M, ST-W48, E-11D, EE-3, E-11, A280, CR-2, F-11D, E-5, A280C, EE-4, EL-16, CA-87 Shock Blaster
- **Heavy (6):** TL-50 Heavy Repeater, Z-6 Rotary Cannon, RT-97C, DLT-19, T-21, Bowcaster
- **Longarms (6):** Valken-38X (BF2), T-7 Ion Disruptor, A280-CFE, NT-242, DLT-20A, IQA-11
- **Jedi: Survivor blasters (15, pistols):** Caij Vanda, Combustion, Enforcer, K3 Vindicator, RSKF-44, Showdown, DL-44, Skeleton Key, Blood
  Eagle (working name), LW-896, Model 13, Swoop, Quickdraw, Arakyd Heavy, Bode's Blaster

## Requirements
- STAR WARS Zero Company on Steam.
- **The ZCSDK Runtime 0.11 or later** (required for the current game version, build 197649). The new Armoury parts are listed only after the Runtime's rescan; without it the game loads the pack but the
  new blasters do not appear. Get it with **Mod Command** (from our GitHub or Discord), or download the Runtime directly:
  https://github.com/EnvianMods/ZCSDK-Runtime-Release
- **Optional: ZCUnlocked** (1.4.72 or later). Its Bolt Color row recolours our bolts.

## Install
**With Mod Command:** install `ZCUltimateBlasterWeaponPack_v1.0.0_gfp.zip`.

**By hand (the game closed):** extract the zip's `ZCUltimateBlasterWeaponPack` folder into
`...\Star Wars Zero Company\SWZeroCompany\Mods\`, so that you have
`SWZeroCompany\Mods\ZCUltimateBlasterWeaponPack\ZCUltimateBlasterWeaponPack.uplugin`. Start the game.

**Uninstall:** with the game closed, delete `SWZeroCompany\Mods\ZCUltimateBlasterWeaponPack`. A character holding one of these weapons
falls back to a stock weapon.

**Do not also install the ZCUnlocked add-on edition of this pack.** Use one edition or the other.

## Using it
Armoury → pick an operator → the weapon slot → CHANGE (the new models sit on the Pistol / Rifle / Repeater / Longarm shelves) →
CUSTOMIZE for paint and colours. Save after changing weapons.

## Known limits in 1.0
- **The Z-6** fires from the shoulder like the game's repeaters.
- **DL-44 (Survivor):** its scope sits on the gun's left side.
- **With ZCUnlocked's Bolt Color row on,** a paint finish (material type, e.g. metallic) and a bolt colour can't be equipped at the same time. They share the second colour slot, so picking one drops the other. This affects stock blasters too and has been reported to ZCUnlocked's author. `boltcolor=0` in ZCUnlocked's `settings.ini` under `[Blasters]` restores the normal finish behaviour (without Bolt Color).
- Overrides: the pack replaces the game's 16 shared attachment palettes (Barrel / Cell / Scope / Stock 02–05) to add its guns' entries.
  Another mod that replaces the same files conflicts with it; the one loaded last wins.

## Credits

- **Silent_SFM**, our Discord member, for decompiling the game and collecting all of the assets.
- **Community model creators.** All 54 blasters in this pack are models from the two games below; it contains no community-made
  models. The community-made lightsabers are credited in the ZC Complete Saber Weapon Pack.
- **Source library:** the "StarWarsPackage" (Star Wars Virtual Production Package) Google Drive project and its contributors.
- **Envian**: the mod's author. Built with the **Zero Company Mod SDK (ZCSDK)** by Envian.
- **ZCUnlocked** by SmexyXey (optional companion).
- **STAR WARS Zero Company** by Bit Reactor / Electronic Arts.

## Sources and legal
- The original models and textures are from **Star Wars Battlefront II (2017)** (© Electronic Arts / DICE) and **Star Wars Jedi:
  Survivor** (© Electronic Arts / Respawn Entertainment). Star Wars © Lucasfilm Ltd. / Disney. This is a non-commercial, fan-made mod,
  not affiliated with or endorsed by any of them.

Free to use in your own games and videos. Please check with me (Envian) first before re-uploading, modifying, or including any part of this pack in another mod.

## Changelog
- **1.0.0** — first public release: 54 blasters (39 Battlefront II, 15 Jedi: Survivor).
