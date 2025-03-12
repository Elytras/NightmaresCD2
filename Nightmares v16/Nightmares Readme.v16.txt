About Nightmares:

Current version 0.6.16
Last change:
Fake leeches maxspawncount set to 5
Changed the way wave 1 and 2 work:
During: 
    Swarms,
    Defend,
    Drillevator,
    Extraction,
    PE countdown
Spawns randomly between 30 seconds and 75 seconds.
During extraction is between 30 seconds and as much as 135 seconds, decreasing in maximum delay by 5 seconds every minute
Every downed dwarf adds 30 seconds of delay
Otherwise:
    On:
        Mining,
        Refinery,
        DeepScan,
    Highest delay is 100 seconds + 30 seconds for each downed dwarf
    Otherwise:
    Highest delay is 90 seconds + 30 for each downed dwarf. base decrease in delay is 2.5s per minute, goes down to as low as 1s per minute
    Lowest delay is down to 1 minute + 30 seconds for each downed dwarf
Changed the way wave difficulty is chosen

Normal waves are turned on again on missions with announced swarms
Removed megulk from enemy pool, added into wave 5  as a 50% to be spawned instead bulkonator
Invisible mini bulk
MaxSpawnCount decreased from 10 to 1
DifficultyRating decreased from 75 to 50
Exploder MaxSpawncount set to 20
Invisible oppressor now resists disintegrate damage type, so now its almost true melee enemy
Invisible oppressor now dies to a single power attack regardless of player count
God oppressor now turns 40% slower

God oppressor breakpoint changes (4 player scaling):
Now dies in 
3 mags of 23321 ER bulldog
3 mags of 23321 VB bulldog
2 mags of 1X13X ER brt
1 mag + 6 bullets of 1X13X LS brt
1 mag of 2X212 JFH | 1.1 mags of 2X211 JFH
------------------------------------------
2 113X1 FM mags
1 11X2X Slast mag | 1 12X22 Slast mag
1 T2C VIM mag
8 Axes
-------
7 Hyperprops
4 T1C nukes
10 T2A/T5B rj250 | 13 T2B/T5B rj250
9 T4B/T5C SPC shots
5 T4B/T5C RTS shots
1 Power Attack + 2 212X1 ODB boosts (electrified) 
2 11111 HAA mags | 2.2 11121 HAA mags
3 11121 EMR mags | 2.3 11121 EMR mags
1.3 22X2X MPA mags | 2.2 12X2X MPA mags 
2 11111 Seeker mags (ignited) | 4 11112 Seeker burst (ignited, ifged)
4 11111 Exec bursts (ignited) | 3 11112 Exec bursts + Power Attack (ignited, ifged)
------------------------------------------------------------------------------------
2 X111X AISE mags | 2 X222X AISE mags
2 X111X BOM mags | 2 X222X BOM mags | 1 X121X BOM mag + ifg
1 2X22X SCC mag + Power Attack | 1 2X22X SCC mag + ifg
2 2X22X hipster mags + ifg | 1.5 2X22X hipster mags (frozen)
150 ammo 32112 TEF 60% - 90% heat | 130 with ifg
140 ammo X2X1X OPA | 110 with ifg
200 ammo X2X1X SBB 
175 ammo 21222 CT (no dot) | 150 ammo 21222 CT + ifg | 150 ammo 21222 CT + fire | 110 ammo 21222 CT + electricity | 96 ammo 21222 CT + electricity + fire | 80 ammo 21222 CT + electricity + fire + ifg | 100 ammo 21222 CT + 2X2X3 ShSh + PA
6 2X23(1/2) Jumbo shots + ifg
2.5 22221 CC mags + electricity | 2 22221 CC mags + ifg
2 Mags of 1123X ED + MFD + IFG | 2.5 Mags of 1123X ED + MFD | 3 Mags of 1123X ED + IFG
3 X1XX2 Trifork shots | 4 XXXX2/X1XXX Trifork shots | 5 Trifork shots

Base Hazard Settings:

    Base Hazard: 6x2.
    Enemy Count: Increased by 10%.
    Egg Ambush: 3.5x enemy count during ambush.
    Extraction & PE Countdown: 1.5x more enemies.
    Damage: Increased by 20%.
    First Resupply: Free, subsequent ones cost 40 nitra each.
    Nitra Modifier: Increased nitra generation based on mission type, cave complexity and mission length.
    Revives: Players revive with 60% HP, regen down to 40% HP.
    Stationaries: 15% more stationary enemies, with a bigger count bin added for Deep Scan, Refinery, and PE missions.
    Swarm Timers: 
    Announced: first 2:10 - 2:40, decrease delay over time, down to 1:30
    Unannounced: disabled on mining/deepscan/refinery, increased frequency on other mission types. delay between waves decreases overtime down to 45 - 60s
    Small Veterans: 3% more on average.
    Large Veterans: 10% less.
    Diversity: Significantly increased wave and stationary diversity.

Global Enemy Changes:

    Breeders and Bombers: Freeze with 1 cryo grenade.
    Bots: Die when frozen; increased freezing temperature.
    Leeches: Take 25% piercing damage; fake and sleeping variants added as decoys.

Specific Enemies:

    Greg™: Large, fast swarmer with high HP, doesn't die when frozen.
    George™: Small Mactera Radialjaw, fast movement, slow to shoot, hard to freeze, very high HP.
    Gabriel™: Giant Oppressor with fast attack speed, very fast movement in straight lines, very slow when turning, normal HP.

Vanilla Enemies:

    Swarmers: HP reduced to 5, 60% smaller, fear and stun immune, don’t die when frozen.
    Normal Grunts: Replaced with White Grunts (no special traits).
    Macteras: Replaced with Cyan Macteras, which electrify on hit.
    Acid Spitter: Can promote into Fire/Ice/Bouncer Spitters.
    Web Spitter: Can promote into Cyan/Pink/Stagger/Gritter Web Spitters.
    Goo Bomber: Can promote into Mactera Buffer or Parabomber.
    Fire Bomber: Added, promotes into Arbabomber or Exploder Spawner.
    Breeder: Now spawns Grabbers. Veteran variants spawn instant/invisible Grabbers.
    Exploders: Can promote into Frost/Fungus variants.
    Nexus: Spawns White Exploders, 1.25x time dilation, 0.75x size.
    Stalkers: Now stunnable for 45% of stun duration, time dilated by 1.05x.
    Stingtails: Take 2x damage, time dilated by 1.5x.
    Patrol Bot: Replaced by Caretaker’s Patrol Bot, promotes into Rocket Barrage Bot or Rocket Beam Bot.
    Youngling: Limited to 1 spawn.
    Grabbers: Replaced with Slow Grabbers, adds instant, invisible, and fake Grabbers.
    Barrage Infector: More expensive to spawn on escort missions.
    Leeches: Instant and infinite instant leech variants added (doesn’t spawn solo or in refineries).
    Big Shredder: Added.
    Immortal Exploder: Added.

MEV Enemies:

    Cyan Grunts: Take 65% damage from cold, 50% from electricity.
    Red Grunts: Take 65% from fire, 50% from explosion.
    Yellow Grunts: Take 35% from corrosion, 50% from poison.
    White Grunts: Normal grunts are 1.25x time dilated and 0.75x in size. slashers are 0.5x in size. guards are 1.5x time dilated
    Fire/Electrical Praetorian: Veterans of Red/Yellow or Cyan/White Grunts, soft-limited to 3 spawns.
    Praetorian Buffer: Added.
    Red (God) Oppressor: Max speed reduced to 80%, 500% acceleration, 250% turn speed, takes 50% kinetic damage, 75% fire damage, and 45% from all other types.
    White (Mini) Oppressor: 75% scale, 2x time dilated, takes 2x more damage.
    Cyan (Invisible Melee Only) Oppressor: Takes melee damage only, invisible.
    Yellow (Elemental) Oppressor: Time dilated 1.5x, takes 2.5x more damage from Driller’s primaries, radiates heat when ignited.
    Frost/Poison/Fire/Electrical Menaces: Added, can promote into Fanatic and Shotgun Menace.
    Macteras: Frost/Poison/Fire/Electrical variants, can promote into their respective Brundle/Trijaw forms. Smaller "swarmer" variants used in custom waves.
    Goo Bomber Buffer: Added.
    Yellow/Red/Purple/Green Breeders: Each spawns shredders, invisible exploders, webspitters, or stabber vines.
    Frost/Fungus Exploders: Added.
    Big (Megulk) Bulk Detonator: 1.5x size, max speed reduced to 40%, takes 75% damage from most types and 25% from piercing. Weakpoint HP is 1500.
    Elemental Bulk Detonators: Fire/Poison/Cold variants added with unique damage resistances.
    Small (Invisible) Bulk Detonator: Scaled down by 75%, low HP, invisible.
    Ice Bulk: Added, scaled 0.9x, time dilated 1.1x.
    Plantonator (Bulkonator): Added, takes 11x damage, spawns mini bulks on death.
    Nexus Variants (Yellow/Green/Purple/Red): Spawn unique enemies like Stingtails, Mactera Brundles, Stalkers, and Turbo Menaces.
    Rocket Barrage/Beam Bots: Added.

DEA Enemies:

    Glasher: Added, promotes into Guardian and Grooter.
    Fire/Ice Spitters, Bouncer, Grooter: Added, selected randomly per spawn event.
    Fanatic: Added, promotes into Shotgun Menace. Low HP, 0.75x size, takes 2x more damage, time dilated 2x.
    Trundle/Pentajaw: Added.
    Mactera Breach Shooter: Promotes into Breach Cutter Brundle.
    Goo Bomber Noshoot: Low HP, immortal weak point.
    Parabomber/Arbabomber: Added, with Greg Jr. and exploder spawns.
    Nukopter: Multiple variants, for stationary or custom waves.
    Drone Breeder/Spitballer Exploder/Guardian: Added.
    White Web Spitters: Custom wave only, promotes into variants like pink/cyan/gritter.

Custom Waves:

    Global: Grow in strength over time. Growth rate changed based on mission type, cave complexity and mission length.

    Wave 1: Random wave selection: Mactera, Grunt, or Ranged waves. Power increases over time during extraction. Disabled during announced swarm.
    Wave 2: Random wave between Invisible, Exploder, Nukopter, or Bot wave. Invisible grabbers removed in solo. 
    Wave 3: Invisible Exploder spawns under a random player every 30 seconds to 5 minutes.
    Wave 4: Mini-bosses (Greg, George, or Gabriel) spawn every 5±2 minutes. Decreases interval during extraction to as low as 30 seconds.
    Wave 5: Bulkonator wave with 10% chance to spawn every 3 minutes. Disabled on defend, drillevator, or escort missions.
    Wave 6: Random wave increases in strength over time, spawning enemies every 30 seconds.
    Wave 7: Wave of a giant immortal stationary praetorian/oppressor and several small ultrafast lootbugs that headbounce you, also magma maggots and harvesters