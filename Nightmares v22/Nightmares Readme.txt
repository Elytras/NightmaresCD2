About Nightmares:

REQUIRES MEV 5.4, DEA b0.0.3, EEE, CD2 14b.
Intended for VWA/VEA

Current release 22
Current version 0.23
Increased veteran chance on grunts, macteras, opperssors
Bulks spawned by bulkonator no longer spawn resource terrain
Swarmers reverted to die when frozen.
Banned golden lootbulks from salvage 
Barrage exploder increased cost at bast from 150 to 165
Barrage exploder increased cost to 190 on PE and Refinery
Spitwaller increased cost from 225 to 275 on PE,Refinery and Escort
Supply cost is now 20/60 instead of 0/40
Nitra count doesnt change with player count (constant 1)
Refinery has extra 0.1 NitraMultiplier
Refinery on 3+ players has -0.1 ECM
+5 Seconds for wavespawners on Refinery
Telenexus removed from refinery
Ice vartok removed from refinery


Base Hazard Settings:
    Base Hazard: 7x2, With hazard 6 health.
    Enemy Count:
        Custom additional increase based on mission type/events.
        worth noting: 3x during egg ambush. up to x2.5 during extraction. increasing enemycount during multi-stage events like caretaker fight or heartstone defend
    Resupply Cost: 0 first, 20 second, 40 every other
    Health: Players revive with 15% HP, 6 HP/S regeneration. 6s delay after getting hit, 60% max regeneration
    Swarm Timers: Custom swarm timers for encouraging faster gameplay

Global Enemy Changes:

    Breeders and Bombers: Freeze with 1 cryo grenade. (With few exceptions)
    Bots: Die when frozen;
    Leeches: Take 25% piercing damage; fake variant added as decoys.

Enemies:
    Swarmers: HP reduced to 5, 60% smaller, fear and stun immune, don’t die when frozen.
    Normal Grunts/Guards/Slashers: Randomly get extra 35% fire/cold, 50% elecric/explosion/poison, 65% corrosive resistances. Can promote into glasher/guardians
    Macteras(MEV): Projectile replaced with random elemental projectile, that randomly ignites/freezes/poisons/electrifies you.
    Acid Spitter(EEE): Have lower hp, randomly shoot freeze/poison
    Web Spitter(DEA): Projectiles replaced with random debuff projectile, that randomly webs/stuns/unshields/mfds you.
    Menaces(MEV/DEA/EEE): Projectile replaced with random elemental projectile, that randomly ignites/freezes/poisons/electrifies you. Can promote into rocket/tcf/turbo/turbonuke/fanatic/teleporter variants
    Goo Bomber(MEV/DEA/EEE): Has NoShot/Acid/Spawner variants
    Fire Bomber(DEA/EEE): Added, Has Arbalest mines and exploder spawning variants
    Breeder(EEE): Added different variants which may spawn Grabbers/Exploders/Elite spitters/Stabbervines/Shredders/Sharks/Sentinels or shooting drones/rockets/nukes
    Exploders(MEV/EEE): Normal exploders removed, Now spawn camouflage normal/radioactive variants or fungus/snow/immortal variants
    Nexi(EEE): Spawn Telegrabbers/Turbomenaces/Exploders/Invisible bulks/Fire or Ice septics
    Stalkers: Now stunnable for 45% of stun duration, time dilated by 1.05x.
    Stingtails: Take 2x damage, sped up 1.5x.
    Patrol Bot(MEV): Replaced by Caretaker’s Patrol Bot, promotes into Rocket Barrage Bot or Rocket Beam Bot.
    Shellback(MEV): respawns or downgrades to youngling, has elemental attacks
    Grabbers(EEE): Removed normal grabbers, added Slow/Instant/Invisible/Dropper variants.
    Barrage Infectors(EEE): Added arbalest mine/Exploder or Bee spawning/nuke variants
    Leeches(MEV/EEE): Removed normal leeches, replaced with invisible or camouflage leeches with extra range/speed
    White Grunts(MEV): Normal grunts are 1.25x time dilated and 0.75x in size. slashers are 0.5x in size. guards are 1.5x time dilated
    Fire/Electrical Praetorian(MEV): Added.
    Praetorian Buffer(MEV): Added.
    God Oppressors(EEE):  Max speed reduced to 80%, 500% acceleration, 250% turn speed, takes 50% kinetic damage, 75% fire damage, and 45% from all other types. Spawns fire when hit and after death
    Mini Oppressor(EEE): 75% scale, 2x time dilated, takes 2x more damage. Spawns Snow cloud on death
    Stalker Oppressor(EEE): Takes melee damage only, invisible, On death spawns field that disables player shield.
    Bouncer Oppressor(EEE): Has increased knockback power.
    Goo Bomber Buffer(MEV): Added.
    Big (Megulk) Bulk Detonator(MEV): 1.5x size, max speed reduced to 40%, takes 75% damage from most types and 25% from piercing. Weakpoint HP is 1500.
    Kinetic Bulk Detonator(EEE): nearly immune to elemental damage, very weak to kinetic damage types
    Elemental Bulk Detoantor(EEE): nearly immune to kinetic damage, very weak to elemental damage. Spawns random elemental field after death
    Invisible bulk detonator(EEE): added
    Ice/Fire/Goo/Leadburster/Bulkonator/Explosive(EEE): added
    Glasher/Guardian(DEA): Added, can be elite.
    Fire Spitter(DEA):  Added, randomly shoots Fanatic fireball or rj250 shot.
    Grooter/Gritter(DEA): Added. Grooter shoots same as acid spitter, Gritter shoots same as web spitter
    Fanatic(DEA): Low HP, 0.75x size, takes 2x more damage, time dilated 2x.
    Greg™(EEE): Giant swarmer with high damage, speed and health
    George™(EEE): Small Mactera Radialjaw, fast movement, slow to shoot, hard to freeze, very high HP.
    Gabriel™(EEE): Wide high speed small oppressor
    Spitwaller(EEE): spitballer variant that shoots custom lacerator stomps at players with combined burst and shotgun attack
    Big Shredder(EEE): Big high hp shredder. Dies and pops into small amount of normal shredders
    Snowptic spreader(EEE): Shoots snowballs that freeze players
    Instant grabbers(EEE): Short hold duration but really fast
    Freezing sprout(EEE): shoots bosco ice rockets
    Instant leech: Leech variant with instant speed.
    Infinite leech: instant leech variant that has infinite range.
    Freezing vartok(EEE): shoots modified bosco ice rockets.
    Spitballers: (MEV/EEE): Added different nuke variants/nemesis shield, lacerator stomp, scorching tide variants
    
    Custom Waves:
    Wave 1: Mini-bosses (Greg, George, or Gabriel) spawn every 5±2 minutes. Decreases interval during extraction to as low as 30 seconds.
    Wave 2: Bulkonator/Megulk wave with 10% chance to spawn every 3 minutes. Disabled on defend, drillevator, or during escort mission stops.
    Wave 3: Grunt Wave. Increases in speed overtime, can spawn as often once every 1.5 minutes.

first test version i hope that i hope has some stuff at least somewhat not buggy
cd2 EEE module:
available fields

IsNightmares (mutable, doesnt reset changed state back, but if off will stop new stuff from being changed) bool
DebugMode (not mutable, for extra logging, may and probably will lag a lot due to logs. for even more logs, while having it at true, enable Verbose Logging in DRGLib)bool
Drunker submodule
    SoberingStrength (mutable) int or "Default" (byte (0-100) ) how much will you sober up (on spacerig default = 0; in mission = 1)
    SoberingCooldown (mutable) float or "Default" (24) how many seconds before sobering ticks
Enemies submodule
    Does not create/destroy descriptors for cd2 "Enemies" module.
    Descriptors you set are expected to either be in the game by default, or added via "Enemies/NoSync" modules
    Nexus submodule
        Materials (mutable)string array 
            for fast material application on nexi, if you dont care about eye materials being different. needs only 3 strings, doesnt (or shouldnt at least) do if more
            available special strings:
            "", "Default" for default material in slot
            "Random" for random material in slot, will be random for each new nexus spawned, will also get updated if you change difficulty
            "camo" "camouflage" self explanatory
            requires enemy to have EEE custom nexus base. (ED_Nexus string in SU should show all of the EEE nexus descriptors, those need to be used as enemy base)
   Warden submodule
        Note: requires warden to have base of EEE custom warden, or its child actors
        WardenSpawn map String -> (mutable)Float :: map of descriptors to their weight of being chosen during warden spawn event. custom veterans are not guaranteed to work properly.  
        ScaleToDifficulty (mutable)bool :: should SpawnCount be multiplied by ECM? 
        SpawnCount (mutable)int :: amount of enemies to spawn
        SpawnRadius (mutable)float :: in what radius
        OverrideSTE (mutable)String :: what status effect should be applied on buffed enemies. Note: not all effects are possible to be applied on enemies 
        OverrideMaterial (mutable)String :: what material should be applied to buffed enemies. Available special strings: random,camouflage.

What to expect:
    removing descriptor from EEE Enemies module will reset it to its base state
    removing submodule inside descriptor from EEE enemies will reset that part of enemy to base
    removing variable from descriptor from EEE enemies submodule will reset said variable to its original state
    removing submodule from EEE module will reset it to vanilla state
    removing EEE module will completely remove any EEE based changes
    any EEE module enemy customization should work when the mission starts, shouldn't require triggering an update in difficulty in any way
    no crashes, lol
    camouflage doesnt work in SU
    lag if you type in the cd2 difficulty with EEE module. on every keystroke cd2 triggers entire difficulty update (EEE setup is quite expensive in return for very cheap execution during mission) so repeteadly triggering updates can and will be quite bad, i advise to change stuff externally
    undefined behaviour if you try to use descriptor that wasnt added by cd2. cd2 modules are built in the way they dont know anything about each other, this includes EEE module. nothing is warranted when you attempt to use descriptor that doesnt exist in cd2 registry
    "EEE Carver:Descriptor" just exist in the logs, they are not implemented, you can ignore whatever they say

If found bug: try to log the way to reproduce. preferably with screenshot or video. 
before reproducing bug enable DebugMode and optionally Verbose in DRGLib. after reproduction of bug attach latest log from FSD\Mods\DRGLib\Logs or make a screenshot of DRGLib logging in the uui/modhub
