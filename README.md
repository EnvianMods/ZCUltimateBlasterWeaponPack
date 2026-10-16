# ZC Ultimate Blaster Weapon Pack 1.2.0 (standalone)

**54 new blasters for STAR WARS Zero Company**, each a real weapon of its own in the Armory, with its own model, name, icon, stats,
bolt color and firing sound. 39 come from Star Wars Battlefront II (2017) and 15 from Star Wars Jedi: Survivor.

The lightsabers are a separate mod, **ZC Ultimate Saber Weapon Pack** (coming later).

- Version 1.2.0, for game build 197649 (Steam).
- Author: Envian. Built with the Zero Company Mod SDK.

## What you get
Each blaster is a new MODEL on the Pistol, Rifle, Repeater or Longarm shelf, beside the game's own guns. The Z-6 Rotary Cannon has a
shelf of its own, "Rotary Blaster Cannon". Each blaster has its own meshes, eight paint patterns on the body and barrel, its own numbers
and bolt color, and it takes the game's attachment modifications (drawn with the gun's own Battlefront II pieces where it has them).

- **Its own real firing sound**, from the game its model comes from, in a sound bank of its own. 36 guns fire their own Star Wars
  Battlefront II (2017) recordings. The 15 Jedi: Survivor blasters fire Jedi: Survivor's own shots: Bode's Blaster and the Caij Vanda
  Blaster have their own, and the other 13 (builds of Cal's blaster in that game) share Cal's default blaster shot. The DC-15A and
  DC-15S use Jedi: Survivor's DC-15 sound, and the Bryar Pistol its own sound from Star Wars Battlefront (2015). Rifles and repeaters
  play a sound for every bolt. The pack's loudness sits close to the game's own blasters.
- **Full bursts.** The rifles and repeaters fire their full bursts, with varied burst patterns like the game's own guns, without
  lowering the gun mid-burst.
- **The Z-6 at the hip.** The Z-6 Rotary Cannon is held at the hip while idle, in Overwatch, while aiming, when it turns to a new
  target and while firing, with a kick on every bolt.

- **Pistols (12):** Bryar Pistol, SE-44, Blurrg-1120, DL-44, DH-17, SE-14C, RK-3, EC-17, DC-17, Glie-44, Relby-K23, Defender Sporting Blaster
- **Rifles (15):** DC-15A (BF2), DC-15S, DC-17M, ST-W48, E-11D, EE-3, E-11, A280, CR-2, F-11D, E-5, A280C, EE-4, EL-16, CA-87 Shock Blaster
- **Heavy (6):** TL-50 Heavy Repeater, Z-6 Rotary Cannon, RT-97C, DLT-19, T-21, Bowcaster
- **Longarms (6):** Valken-38X (BF2), T-7 Ion Disruptor, A280-CFE, NT-242, DLT-20A, IQA-11
- **Jedi: Survivor blasters (15, pistols):** Caij Vanda, Combustion, Enforcer, K3 Vindicator, RSKF-44, Showdown, DL-44, Skeleton Key, Blood
  Eagle, LW-896, Model 13, Swoop, Quickdraw, Arakyd Heavy, Bode's Blaster

## Download
| file | size | md5 | sha256 |
|---|---|---|---|
| `ZCUltimateBlasterWeaponPack_v1.2.0_gfp.zip` | 538,854,057 bytes (about 539 MB) | `0cecb49086c7f7437c3f293f042e86ca` | `54b3aeec02fa0590d39360d593c5d5bb78690042f8edd11b77bb85b9ac02a3b4` |

## Requirements
- STAR WARS Zero Company on Steam.
- **UE4SS for Star Wars Zero Company** ([Nexus mod 9](https://www.nexusmods.com/starwarszerocompany/mods/9), by Vercadi): required by
  the Runtime. Install it first.
- **ZCSDK Runtime 0.13** (0.11 or later works on Windows; 0.13 is recommended, and Linux / Steam Deck needs it): required for the
  current game version, build 197649. The new Armory parts are listed only after the Runtime's rescan; without it the game loads the
  pack, but the new blasters are not listed in the Armory. Get it with **Mod Command**, or download it directly:
  https://github.com/EnvianMods/ZCSDK-Runtime-Release/releases/latest
- **Fully compatible with ZCUnlocked** (1.4.72 or later, optional): its Bolt Color row recolors these blasters' bolts, in the Armory and in missions.

## Install
**With Mod Command (recommended):**
1. Use the latest Mod Command.
2. Settings > **ZCSDK Runtime** > Install / Update. It installs UE4SS for Star Wars Zero Company first if needed, then the Runtime.
3. Install `ZCUltimateBlasterWeaponPack_v1.2.0_gfp.zip`.

**By hand (the game closed):**
1. **UE4SS first:** install [UE4SS for Star Wars Zero Company](https://www.nexusmods.com/starwarszerocompany/mods/9) as its page
   describes: extract its full zip into `SWZeroCompany\Binaries\Win64\`, so `dwmapi.dll` and a `ue4ss` folder sit next to
   `SWZeroCompany.exe`.
2. **Then the ZCSDK Runtime:** from the [latest Runtime release](https://github.com/EnvianMods/ZCSDK-Runtime-Release/releases/latest),
   download the zip with "_manual" in its name (now `ZCSDKRuntime_v0.13_manual.zip`; the other zip is for Mod Command) and extract it
   into the **same** `SWZeroCompany\Binaries\Win64\` folder. Its `ue4ss` folder merges into UE4SS's. Do **not** extract it into
   `ue4ss\Mods`. After this, either one can be updated without reinstalling the other.
3. **This mod:** extract the zip's `ZCUltimateBlasterWeaponPack` folder into `...\Star Wars Zero Company\SWZeroCompany\Mods\`, so that
   you have `SWZeroCompany\Mods\ZCUltimateBlasterWeaponPack\ZCUltimateBlasterWeaponPack.uplugin`. Start the game.

**Updating from Runtime 0.10 - 0.12?** Mod Command: Settings > ZCSDK Runtime > **Reinstall**. By hand: extract the latest manual zip,
then **reinstall UE4SS (mod 9) and let it replace all files**. The older Runtimes overwrote three of UE4SS's own files, which makes
ZCUnlocked report an "old build of UE4SS".

**Updating from 1.0.0 or 1.1.0:** install 1.2.0 over it (Mod Command), or with the game closed delete
`SWZeroCompany\Mods\ZCUltimateBlasterWeaponPack` and extract the new one. The Z-6 moved to its own class, so a character who had it
equipped needs it again: Armory, the operator, the weapon slot, the Z-6 under "Rotary Blaster Cannon", then a manual save. The other
blasters and their paints carry over.

**Linux / Steam Deck (Proton):** use Runtime 0.13 or later, and add the Steam launch option given in
[the Runtime's README](https://github.com/EnvianMods/ZCSDK-Runtime-Release).

**Check it worked:** `ue4ss\ZCSDKLoader.log` has a `manifest:` line for ZCUltimateBlasterWeaponPack. With ZCUnlocked,
`ue4ss\Mods\ZCUnlocked\dlls\ZCUnlocked.log` should say `verdict=ok`; `verdict=old` means reinstall UE4SS (mod 9). **Blasters not
listed?** The Runtime is missing or not loaded; see [the Runtime's README](https://github.com/EnvianMods/ZCSDK-Runtime-Release) for
troubleshooting.

**Uninstall:** with the game closed, delete `SWZeroCompany\Mods\ZCUltimateBlasterWeaponPack`. A character holding one of these weapons
falls back to a stock weapon.

## Using it
Armory, pick an operator, the weapon slot, CHANGE (the new models sit on the Pistol / Rifle / Repeater / Longarm shelves, the Z-6 on
Rotary Blaster Cannon), then CUSTOMIZE for paint and colors. Save after changing weapons.

## Known issues
- **The Z-6 is still held at the shoulder while crouching and while running.** A fix is planned for 1.2.1.
- **Long echoes:** the Jedi: Survivor and DC-15 sounds keep their game's outdoor echo, so they ring out longer than the Battlefront II
  sounds.
- **DL-44 (Survivor):** its scope sits on the gun's left side.
- **With ZCUnlocked's Bolt Color row on,** a paint finish (material type, e.g. metallic) and a bolt color can't be equipped at the same time. They share the second color slot, so picking one drops the other. This affects stock blasters too and has been reported to ZCUnlocked's author. `boltcolor=0` in ZCUnlocked's `settings.ini` under `[Blasters]` restores the normal finish behavior (without Bolt Color).
- **Conflicts:** the pack replaces the game's 16 shared attachment palettes (Barrel / Cell / Scope / Stock 02-05) to add its guns'
  entries, and the game's firing animation table (`DT_AG_TypicalShot_MASTER`) so that each rifle and repeater plays its full burst
  animations. Another mod that replaces any of the same files conflicts with it; the one loaded last wins.

## Credits
- **Silent_SFM**, our Discord member, for the original rip of the game assets.
- **Sounds:** 36 guns use ripped Star Wars Battlefront II (2017) weapon audio from the "StarWarsPackage" collection.
  The other 18 use sound effects from Star Wars Jedi: Survivor and Star Wars Battlefront (2015).
- **Community model creators.** All 54 blasters in this pack are models from the two games below; it contains no community-made
  models. The community-made lightsabers are credited in the ZC Ultimate Saber Weapon Pack.
- **Source library:** the "StarWarsPackage" (Star Wars Virtual Production Package) Google Drive project and its contributors.
- **Envian**: the mod's author. Built with the **Zero Company Mod SDK (ZCSDK)** by Envian.
- **UE4SS for Star Wars Zero Company** by Vercadi.
- **ZCUnlocked** by SmexyXey (optional companion).
- **STAR WARS Zero Company** by Bit Reactor / Electronic Arts.

## Sources and legal
- The original models and textures are from **Star Wars Battlefront II (2017)** (© Electronic Arts / DICE) and **Star Wars Jedi:
  Survivor** (© Electronic Arts / Respawn Entertainment). The sound effects are from Star Wars Battlefront II (2017) and **Star Wars
  Battlefront (2015)** (© Electronic Arts / DICE) and from **Star Wars Jedi: Survivor** (© Electronic Arts / Respawn Entertainment);
  they remain the property of their owners. Star Wars © Lucasfilm Ltd. / Disney. This is a non-commercial, fan-made mod, not
  affiliated with or endorsed by any of them.

Free to use in your own games and videos. Please check with me (Envian) first before re-uploading, modifying, or including any part of this pack in another mod.

## Changelog
- **1.2.0**: the Z-6 Rotary Cannon has its own Armory class, "Rotary Blaster Cannon" (re-equip it after updating, then save). The Z-6
  is held at the hip while idle, in Overwatch, aiming, turning and firing, with stronger recoil per bolt and the feet planted. The pack
  is quieter, closer to the game's own blasters; the T-7 was turned down the most. Updated weapon icons. Known issue: the Z-6 is still
  at the shoulder while crouching and running (fix planned for 1.2.1).
- **1.1.0**: every blaster has its own real firing sound from its source game (Star Wars Battlefront II (2017) for 36 guns; Jedi:
  Survivor for the 15 Survivor blasters and the DC-15A / DC-15S; Star Wars Battlefront (2015) for the Bryar Pistol), one compressed
  (ADPCM) sound bank per gun. Rifles and repeaters play a sound per bolt. Rifles and repeaters no longer lower the gun mid-burst: full
  bursts with varied burst patterns, like the game's own guns. The Z-6 Rotary Cannon fires its full burst from the hip. Bigger download
  (the sounds). Replaces 1.0.0.
- **1.0.0**: first public release: 54 blasters (39 Battlefront II, 15 Jedi: Survivor).
