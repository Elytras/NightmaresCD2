About Nightmares:

Current version 0.8.0
Last change:
Removed cyan/red praetorians from being promotions of grunts. increased cyan/red praetorian MaxSpawnCount from 0/1/2 to 2/4, removed soft-limit, rarity decreased from 5 to 3
Removed oppressors from EnemyPool, leaving only being able to spawn as praetorian promotions
Replaced normal menace with RandomChoice between normal menace and elemental menace variants
Banned some anomalies and warnings
Added grunt as a wave 1(all waves shift their number up)
Removed grunts from wave 2(prev: 1)
Locations of custom waves 2,3 are set to 2
In wave 1, added "diversity variability"
VeteranLarge 0.18 to 0.25 
Enemy Caps changed to be 100/150/240/300 on 1/2/3/4 players respectively, double during egg ambush
Grunt DifficultyRating 3 to 3.5
Fixed downed dwarves bonus time not working properly
Fake Bomber rarity set to 7
Decreased rarity of "stationary" breeders from 4 to 3, decreased rarity of mactera and exploder nexi from 4 to 3
Replaced with invisible bulk nexus
    Limited to 5 spawns
Decreased difficultyrating of nukeballers, nukopters and some nexi
Difficultyrating of white webspitter from 5 to 4
Fire bombers rarity 9 to 9.25, MaxSpawnCount 9 to 3
Exploder MaxSpawnCount 20 to 16
Invisible Oppressor MaxSpawnCount from 1 to 0
Removed Patrol bot from pool
Swarmer Size from 0.4x to 0.6x
Replaced some of DamageMultipliers for Heaalthmultiplier to make disintigrate damage work
Fixed Arbabomber and Explomber not having breakpoints
Removed Stun Multipliers from Explombers
Removed grunts from promoting into other elemental grunt variants
Rewritten intervals
Increased Strafe,Acceleration,MaxSpeed for bulks
Decreased rarities on a lot of disruptive and special enemies
Set Grunt and Exploder significance to Swarmer in order to stop them from despawning other enemies
Replaced Brundle Nexus with Instant Grabbers nexus
Replaced Stingtail Nexus with Septic Spreader nexus
Replaced Stalkers with Invisible bulk nexus
Added NoSpawnWithin 5m for bulks to stop unstoppable tpk (mostly salvage)
Replaced white spitters in EnemyPool with randomchoice of other spitters
Replaced acid spitters in EnemyPool with randomchoice of other spitters
Replaced Glashers promoting grooter variants from normal to wall
Replaced grooter material to be glowing in the dark
Added bossbar to Shotgun menace
Removed MaxSpawnCount for trijaws and them being able to promote into trundles

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
    Goo Bomber: Can promote into Mactera Buffer, Parabomber or Acid Bomber.
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
    Fire/Electrical Praetorian: soft-limited to 4 spawns.
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
    Nexus Variants (Yellow/Green/Purple/Red): Spawn unique enemies like Stingtails, Mactera Brundles, Invisible bulks, and Turbo Menaces.
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

    Wave 1: Grunt wave.
    Wave 2: Random wave selection: Mactera, Ranged waves, praetorians, special grunts. Power increases over time during extraction. Disabled during announced swarm.
    Wave 3: Random wave between Invisible, Exploder, Nukopter, or Bot wave. Invisible grabbers removed in solo. 
    Wave 4: Invisible Exploder spawns under a random player every 30 seconds to 5 minutes.
    Wave 5: Mini-bosses (Greg, George, or Gabriel) spawn every 5±2 minutes. Decreases interval during extraction to as low as 30 seconds.
    Wave 6: Bulkonator/Megulk wave with 10% chance to spawn every 3 minutes. Disabled on defend, drillevator, or escort missions.
    Wave 7: Random wave increases in strength over time, spawning enemies every 30 seconds.
    Wave 8: Wave of a giant immortal stationary lootbug and several small ultrafast lootbugs that headbounce you, also magma maggots and harvesters