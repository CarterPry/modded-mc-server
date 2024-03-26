# Modded CurseForge Minecraft Server

This is a server that a friend and I set up and played through with about 112 mods. I hosted it from a Linux server, and we used [CurseForge](https://www.curseforge.com/) on the client side to play it.

## Getting Started

To match the server mods with the client, download and upload this [file](https://github.com/CarterPry/modded-mc-server/blob/main/UploadThistoCurseForgeForClientSideModsToPlay.zip) to CurseForge to create a profile compatible with the mods being used.

## Mod List

This is a list of all the mods used on the server. Note that there are additional client-side mods in the profile that enhance gameplay:

- Fluid cows (by ロ_ロ)
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
- No Recipe Book (by Adorn)
- Angel Ring To Bauble (by Portablejim)
- xXx_MoreToolMats_xXx (a PlusTiC fork without the evil, and apparently some new bugs idk) (by TeamDman)
- The Twilight Forest (by Benimatic)
- Mystical Agriculture (by BlakeBr0)
- Ice and Fire: Dragons (by sbom_xela)
- Baubles (by Azanor13)
- Waystones (by BlayTheNinth)
- Mouse Tweaks (by YaLTeR)
- MrCrayfish's Furniture Mod (by MrCrayfish)
- Hwyla (by TehNut)
- Lootr (Forge & NeoForge) (by Noobanidus)
- SuperMartijn642's Core Lib (by SuperMartijn642)
- Controlling (by Jaredlll08)
- iChunUtil (by iChun)
- Carry On (by Tschipp)
- Not Enough Wands (by romelo333)
- Applied Energistics 2 (by thetechnici4n)
- Flux Networks (by sonar_sonic)
- Chameleon (by Texelsaur)
- SecretRoomsMod (by AbrarSyed)
- OpenComputers (by Sangar_)
- Inventory Tweaks [1.12 only] (by JimeoWan)
- MysticalLib (by Noobanidus)
- Avaritia 1.1x (by covers1624)
- Mystical Agradditions (by BlakeBr0)
- Hats (by iChun)
- Shadowfacts' Forgelin (by ShadowfactsDev)
- Botania (by Vazkii)
- Crafting Tweaks (by BlayTheNinth)
- Ender Storage 1.8.+ (by covers1624)
- Chance Cubes (by TurkeyDev)
- Extra Utilities (by RWTema)
- RFTools (by McJty)
- Portal Gun (by iChun)
- MixinBooter (by CleanroomMC)
- Quark (by Vazkii)
- BountifulBaubles (by Cursed1nferno)
- Neat (by Vazkii)
- Xaero's Minimap (by xaero96)
- CodeChicken Lib 1.8.+ (by covers1624)
- Overloaded Armor Bar (by tfarecnim)
- Just Enough Resources (JER) (by way2muchnoise)
- Minecraft Comes Alive (MCA) (by WildBamaBoy)
- Biomes O' Plenty (by Forstride)
- Tesla Core Lib (by face_of_cat)
- Chicken Chunks 1.8.+ (by covers1624)
- SwingThroughGrass (by exidex)
- Waila Harvestability (by squeek502)
- OpenBlocks (by OpenMods)
- Mob Grinding Utils (by vadis365)
- Ender IO (by crazypants_mc_the_second)
- EnderCore (by tterrag1098)
- Collective (by Serilum)
- CC: Tweaked (by SquidDev)
- OpenModsLib (by OpenMods)
- Fast Leaf Decay (by olafskiii)
- Villager Names (by Serilum)
- Mantle (by mDiyo)
- Patchouli (by Vazkii)
- Just Enough Items (JEI) (by mezz)
- Baubley Heart Canisters (by traverse_joe)
- Dark Utilities (by DarkhaxDev)
- Blockcraftery (by EpicSquid315)
- Iron Chests (by ProgWML6)
- McJtyLib (by McJty)
- BetterFps (by Guichaguri)
- Akashic Tome (by Vazkii)
- Cucumber Library (by BlakeBr0)
- Infinity Craft (by tilera)
- More Avaritia (by chocolate_milkk__)
- Storage Drawers (by Texelsaur)
- Lucraft: Core (by Lucraft)
- Too Many Efficiency Losses (by ItsPonks)
- Twerk Sim 2K16 (by Funwayguy)
- Tinkers Construct (by mDiyo)
- EnderTanks (by ShetiPhian)
- Blood Magic (by WayofTime)
- LootBags (by Mina_the_Engineer)
- The Aether (by TheAetherTeam)
- Guide-API (by TehNut)
- Mixin 0.7-0.8 Compatibility (by NotStirred)
- ShetiPhianCore (by ShetiPhian)
- Chisel (by tterrag1098)
- AutoRegLib (by Vazkii)

## Server Launch Command
```
git clone https://github.com/CarterPry/modded-mc-server.git
```
```
cd modded-mc-server
```

Then to run the server on a Linux terminal, use the following command, replacing `[Amount of Ram you want to use]` with the actual amount of RAM you wish to allocate:

```
sudo java -Xmx[Amount of Ram you want to use] -jar forge-1.12.2-14.23.5.2859.jar nogui
```

Example command with `14G` of RAM:

```
sudo java -Xmx14G -jar forge-1.12.2-14.23.5.2859.jar nogui
```
