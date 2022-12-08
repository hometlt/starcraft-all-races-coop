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


## Prestiges


● Raynor                     
  Sniper of Liberty:
 + Raynor is available to lead your army. Uses "Penetration Ammo", "Stims".
 - Hyperion is unavailable.
● Swann                                          
  Experimental Weaponry:
 + Laser tanks is available. After upgrades get abilities. 
 - Laser drill and Laser Drill abilitys unavailable
● Stukov                                            
  ********
 + Stukov is available to support your army.
 -
● Artanis                                                  
  Leader of Khalai:
 + Artanis is available to defend your army. Uses "Lightning Dash", "Resurgence", "Astral Wind", "Force of Will".
 - Shield Overcharge is unavailable 
● Karax                                                    
  Solar Forger:
 + Karax is available to support your army. Uses "Photon Cannons", "Pylon Energy".
 - Orbital Strike is unavailable.
● Vorazun                                                   
  Guard of Shadow Legion:
 + Vorazun is available to support your army. Uses "Shadow Dash", "Shadow Fury", "Veil of Shadows".
 - Deploy Shadow Guard is unavailable.
❂ Stetman 
  Bffs:
 + Stetman is available to support your friends.
 - Units cost incresaed by 50%.
❂ Zeratul                                                       
  Legion of Xel'naga:
 + Max supply increased to 200. Probes now can use vision.
 - Zeratul is unavailable.              
❂ Nova                                                      
  Elite Army:
 + Max supply increased to 200. Cost of units decreased by 25%
 - Nova is unavailable.
❂ Kerrigan                                                                   
  Heart of the Swarm:
 + Max energy increased to 200. Abilities deals 50% more damage.
 - Max supply decreased to 100. Ultralisk is unavailable.
❂ Dehaka                                                                  
  Unpredictable animals:
 + Ravasaur, Primal Igniter, Impaler, Creeper host, Tyrannozor get health increased by 50% and attack by 25%.
 - Dehaka and essence is unavailable
❂ Han & Horner   
  Explosive-Precise Duo:
 + Han on Queen of Assault deals explosive damage to enemy. Horner on Hyperion II deals pinpoint strikes on the enemy, destroying dangerous targets.
 - mag mines & strike fighters is unavailable 
❂ Fenix                                                                   
  Memory Backups:
 + Number of AI personality now unlimited. 
 - AI now not relocate in another body. All AI personality health decreased by 30%
❂ Alarak                                                                  
  One Tyrant-Army:
 + Alarak attacks deal splash damage. Cooldown of Alarak abilities decreased by 50%. When beyond the vision range of all your or ally units, Alarak deal 100% more damage and take 50% less damage.
 - Soul Absorption can't steal life from units you control. Empower Me is unavailable.
❂ Tychus   
  The Robber of the Century:
 + Tychus deals 150% more damage and take 50% less damage. Tychus can accumulate rage by receiving and dealing damage to get bonuses, rage expires quickly if Tychus does not deal and does not receive damage
 - Max Outlaws set to 1. All outlaws is unavailable.
❂ Mengsk                                              
  Heroes of Dominion:
 + Royal Guard health increased by 50% and damage by 30%. Imperial Mandate from Royal Guard gains 200% more.
 - Royal Guard gets limit of 1 of each royal unit. Dogs of War is unavailable.
❂ Abathur                                         
   


❂ Zagara                                                                  





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
🌐Team-P Reveal Index (Mode)
🎯Ally-P Start Index (Mode)
🎯Ally-P Expansion Index (Mode)
📍Wave N-W
📍Evil N-W
⇉Team-P Squad <Index> (Difficulty-Size-Tech-Collide)
⇉Team-P Outpost <Index> (Difficulty-Size-Tech-Collide)
⇉Team-P Base <Index> (Difficulty-Size-Tech-Collide)

🌐Team-P Clear Index (Mode)      //🌐Ally Clear (2)
🌐Team-P Base Index (Mode)
```

Belshir Escort
```
🌐BE Reveal
🌐BE Geyser N
📍BE Park N
BE Spawn
BE Path N-W
BE Spot N
```
Belshir Whales
```
🌐BW Area N
🌐BW Reveal N
BW Spawn
```

### Maps development 
1. сделать переменными ( убрать constant checkbox)
 PLAYER_01_USER = 1 <Integer>
 PLAYER_02_USER = 2 <Integer>

2. в Init 03 Players инициализировать игрока 1 и 2
        Variable -Set PLAYER_01_USER = (Player 1 from (Get Allied Commanders Players()))
        General -If (Conditions) then do (Actions) else do (Actions)
            If
                (Number of players in (Get Allied Commanders Players())) > 1
            Then
                Variable -Set PLAYER_02_USER = (Player 2 from (Get Allied Commanders Players()))
            Else
                Variable -Set PLAYER_02_USER = PLAYER_01_USER (изменено)

3. изменить игроков 3/4/5(пример из miner ecacuation) 
   PLAYER_03_AMON_Claimers = 13 <Integer (Constant)>
   PLAYER_04_AMON_BaseWaves = 14 <Integer (Constant)>
   PLAYER_05_INFESTED_Bullies/Holdout/NeutralToss = 12 <Integer (Constant)>

 оставить загрузку только для игроков 1-5

4. убедится что удален триггер "defeat base dead"

5. Run Victory / Run Defeat нужно убедится что используются Victory/Defeat из модуля Mission(COOP)

 меняешь владельца предстуановленных юнитов игроков 3-5

Player Start 1 - Player Start 5

6. установить точки старта игроков

точки старта амуна Amon Start 1 - Amon Start 2

точка старта игрока будет Player Start <количество игроков>-<номер игрока>, а если нет Player Start <номер игрока> (изменено)

точка старта игрока за Амуна будет Amon Start <количество игроков за амуна>-<номер игрока>, а если нет Amon Start <номер игрока>
НОВОЕ

Optional Zone 1      -    Optional Zone 5    опциональные ресы, юниты для определенного количества игроков командиров

Optional Zone 2-1      Optional Zone 2-2     опициональные ресы для определенного количества игроков амуна

иногда удобно использовать Clear Zone <колво игроков> чтобы удалить ресы

Safety Zone - безопасная о мутаторов зона при любом колве игроков
Safety Zone 1    -     Safety Zone 5     - дополнительные безопасные зоны при конкретном количестве игроков
при игре на 1 . либо 1 экспаншен либо 2 если они в разных сторонах , при игре на 4 игроков одна из экспаншенов амуна будет появлятся. при игре на 5 оба экспаншена амуна .
Initial Exploration [<колво игроков>]    это зона на которой иргоки видят где их экспаншены

при желании предустановить юнитов здания для трех стандартных рас (теры , протоссы зерги )
тут есть список типов предустанавливаемых юнитов COOPAIReplacement
Изображение
ситоит проверить на картах что все юниты заменяются
Изображение
"Doodads Replacement Area"
удалить refinery/assimilators/extractors и рабочих амуна
а еще на основные базы амуна с минералами добавь защитников. например парочку доминаторов)
Изображение
Изображение
Evil <номер маршрута>-<точка на маршруте>
Evil 1-1  , Evil 1-2    -  первый маршрут
Evil 2-1, Evil 2-2  - второй маршрут
Амун - red и dark red

amon neutral - желтый и оранжевый
спицифичные - розовый и фиолетовый 


