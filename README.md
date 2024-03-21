# Modded CurseForge Minecraft Server

This is a server that a friend and I set up and played through with about 112 mods. I hosted it from a Linux server, and we used [CurseForge](https://www.curseforge.com/) on the client side to play it.

## Getting Started

To match the server mods with the client, download and upload this [file](https://github.com/CarterPry/modded-mc-server/blob/main/UploadThistoCurseForgeForClientSideModsToPlay.zip) to CurseForge to create a profile compatible with the mods being used.

## Mod List

This is a list of all the mods used on the server. Note that there are additional client-side mods in the profile that enhance gameplay:

- Fluid Cows (by ロ_ロ)
- SimpleZoom (by UnRealDinnerbone)
- Enchantment Descriptions (by DarkhaxDev)
- Galacticraft Legacy (by TeamGalacticraft)
- Bookshelf (by DarkhaxDev)
- Macaw's Bridges (by sketch_macaw)
- ConnectedTexturesMod (by tterrag1098)
- Star Tech, Man! The Legendary Mod? (by nictogen)
- The Fifth World (by nictogen)
- Xaero's World Map (by xaero96)
- Trash Cans (by SuperMartijn642)
- GunpowderLib (by Jacky)
- RFTools Dimensions (by McJty)
- Cyclic (by Lothrazar)
- Construct's Armory (by TheIllusiveC4)
- LLibrary (by MCModDev)
- Tinkers' Tool Leveling (by bonusboni)
- KleeSlabs (by BlayTheNinth)
- Corail Tombstone (by Corail_31)
- Snad (by TheRoBrit)
- Dank Storage (by tfarecnim)
- Artifacts (by ochotonida)
- Inventory Pets (by Purplicious_Cow_)
- Ore Excavation (by Funwayguy)
- Cosmetic Armor Reworked (by LainMI)
- No Recipe Book (by SeneschalLuwin)
- Angel Ring To Bauble (by Portablejim)
- xXx_MoreToolMats_xXx (a PlusTiC fork) (by TeamDman)
- ... (continue listing other mods as needed)

## Server Launch Command

To run the server on a Linux terminal, use the following command, replacing `[Amount of Ram you want to use]` with the actual amount of RAM you wish to allocate:

```
sudo java -Xmx[Amount of Ram you want to use] -jar forge-1.12.2-14.23.5.2859.jar nogui
```

Example command with `14G` of RAM:

```
sudo java -Xmx14G -jar forge-1.12.2-14.23.5.2859.jar nogui -Dfml.queryResult=confirm
```
