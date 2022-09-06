## install mods
git clone hometlt/all-races-coop <SC2Directory>/mods/all-races-coop






✦ all data and triggers are heavily optimised for much  easier customisation (not stable yet but i am close)
✦ web-based data-editor and some utility scripts which helps in development (merging mods, collecting units data, easy user-data editing). here is a preview of this editor -  http://sc2-all-races.herokuapp.com/
✦ about 50 standaard + RTC2017 maps in th arcadee and in the laucnher (can be found as [ARC], last versions on EU server)
✦ 1-5 commander players modes ( with adjustable resources, splats , adapted maps)
✦ a way to play as Amon . 1-2 Amon players available on each map
✦ Void Balance Mod Integration which adds multiplayer balanced races as commanders (probably will use it later to create a mod with coop factions)  
✦ New Units For Simulan,Dominion,Ihannrii and other Factions
✦ New Factions - Talon Protoss  
✦ Commentators and UI icons for Commanders 
✦ Skins (Nerazim Skins for Vorazun, 5 standard skinpacks per each multiplayer race) 
✦ Additional Enemy Factions , each with specific upgrades, attack waves, preplaced buildings and doodads.
 - Ihanrii, Leviathan, Evolved, Infested, Taldarims, CoverOps, Simulant, Primals, Dominion
✦ Additional races available to play as commanders or can be set as Amon Faction 
 - Keiron, Genetron, Xayid, UED, Hybrids, Dragons, UPL
✦ New prestiges , heroes (mostly conceptual, not very developed) so i am thinking rto bring some ideas from other mods for it:)
✦ customizable enemy attack waves behaviors, additional routes, better spawns
✦ extension (not very developed)
 - WarCraft extension which adds warcraft races commanders and enemy factions 
 - Nexus extension which adds Valerian from Nexus COOP 
✦ and many other things

this is kinda a lot.. but i am making it (mostly) alone and would need some help :slight_smile:
so i think maybe you can find it interesting? 
and Here is my discord server https://discord.gg/UWJJQeJ4 






## Maps Tempalting

#### OLD
```
🎯Player Start [<Teammates>-]<Player>
🎯Amon Start [<Teammates>-]<Player>

🌐
🌐
🌐

```

#### New

🎯 - Start Point
📍 - Point
🌐 - Region

**Team**: Ally|Amon

**Player**: 1-5

**Teammates**: 1-5

**Wave**: Wave|Evil

**Squad**: Base|Outpost|Squad

**Collide**: Ground|Air

**Difficulty**: Peaceful|Casual|Normal|Hard|Brutal|Extreme|Unlikely

**Size**: Smallest|Saller|Small|Medium|Large|Larger|Largest

**Tech**: Lowest|Lower|Low|Middle|High|Higher|Highest
Amon-1 Squad 4 (Largest-Highest-Air)
```
🎯<Team>-<Player> Start [(<Teammates>)]
🎯<Team>-<Player> Expansion [<Index>] [(<Teammates>)]
📍<Team>-<Player> <Wave> <Index>[-<Waypoint>]
🌐<Team>-<Player> <Squad> <Index> [([<Difficulty>]-[-<Size>]-[-<Tech>]-[<Collide>])]
```