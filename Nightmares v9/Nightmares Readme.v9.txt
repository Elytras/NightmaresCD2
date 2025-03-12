About Nightmares:

Current version 0.0.9
Last change:

Using chatgpt for changelog cleanup:

New Enemies:

    Added fake leeches (normal/silent/invisible).
    Added sleeping leeches (normal/silent/invisible).
    Added fake grabber.
    Added acid bomber as a veteran of the normal bomber.
    Added slow sniper turrets.
    Added Gritter as a veteran of the webspitter.

Adjustments:

    Increased stationary diversity.
    Decreased leech difficulty rating for better blending with fake leeches.
    Set MaxSpawnCount for real leeches to 10.
    Removed Plantonator and nukopter from spawning during salvage defend.
    Decreased MaxSpawnCount for praetorians based on player count (3 to 0/1/2).
    Youngling MaxSpawnCount decreased from 3 to 2 (no bowling).
    Decreased max alive shredders spawning from naedocyte shredder: from 30 to 15, burst size from 6 to 3, and jelly spawn count from 8 to 4.
    Removed MaxSpawnCount from spitballer variants.
    Applied escort/refinery restriction to the 5-shot nukeballer.
    Stopped grunts from promoting into praetorian types if more than 3 praetorians of their type are alive.
    Set MaxSpawnCount for elemental and nonelemental bulk to 2.
    Set MaxSpawnCount for Plantonator to 1.
    Set MaxSpawnCount for naedocyte bomber to 3.
    Set MaxSpawnCount for naedocyte webber to 2.
    Set MaxSpawnCount for naedocyte stabber to 2.
    Set MaxSpawnCount for naedocyte shredder to 2.
    Set MaxSpawnCount for naedocyte grabber to 1.

Enemy Pool Modifications:

    Removed god oppressor from the pool; fire praetorian cannot promote if one is on the map.
    Removed invisible (melee only) oppressor; electric praetorian cannot promote if one is on the map.
    Removed mini oppressor; electric praetorian cannot promote if two are on the map.
    Removed elemental oppressor; fire praetorian can promote if four are on the map.
    Nexi (except exploder nexus) now spawn up to 5/10/15/30 enemies on death.

Renaming:

    Renamed grunts, menaces, and macteras according to their element.

Miscellaneous:

    Glyphid megulk detonator can now be seen in encounters.
    Invisible bulks do not show their HP and nametags.
    Nonnexus stingtail and stalker MaxSpawnCount set to 5.

Event Modifications:

    During egg ambush, spawn 3.5x more enemies.
    During extraction and countdown on PE, spawn 1.5x more enemies.
    Added harder Stationary Difficulty bin for PE, Refinery, and Deepscan.

----------------------------------------------------------------------------

Base Hazard:

    Hazard Level: 6x2
    Enemy Count: 10% more enemies
    Damage: 20% increase
    Resupply: First free, then 40
    VeteranLarge Spawn Rate: 0.08
    Revive with 60% HP
    Regeneration: Up to 40%
    Stationary Difficulty: Changed from 350/450 to 400/500

Global Changes:

    All leeches take 25% damage from piercing.

Vanilla Enemies:

    Normal breeders spawn slowed grabbers, can promote veteran variant that spawns invisible/instant grabbers.
    Normal swarmers and grunts removed.
    WebSpitters rarity: Set to 2.
    Stingtails: Take 2x more damage and have 1.5x time dilation.
    Stalkers: Time dilated to 1.05x; stunnable for 45% of stun duration.
    Caretaker's patrol bots added.
    Swarmers: Reduced to 40% of original size, immune to fire/freeze, fear, and stun; promote into MEV swarmer variants; base HP lowered to 5.
    Greg: A large swarmer, 3x time dilation, immune to freeze/fire.
    Greg Jr.: Spawned by DEA Parabomber and Spawnballer.
    Grabbers now available as invisible/instant variants.
    Added infinite instant leech.*

DEA Enemies:

    WebSpitters: Added small veterans of normal webspitter.
    Gritter: Added as a small veteran of normal webspitter.
    AcidSpitters: Added as small veterans of normal acid spitter.
    Goobers/Foobers: Acid goober added as small veteran; Parabomber added as small veteran.
    Naedocyte Drone: Added.
    Goober No Shot: Added with immortal weak points.
    Nukopter: Added as rare stationary and disruptive unit.
    Arabomber & Bomber Exploder: Added as small veterans of Foober.
    Mactera (Not Goobers): Trundle and Pentajaw added as small veterans of Brundles and Trijaws.
    Grunts: Glasher and Grooter added as small veterans.
    Spitballers: Spawner and Bomber added.
    Menace Variants: Added as large veterans of normal menace.
    Turrets: Added sniper turret.
    Miscellaneous: Stabber Vines added as egg spawns from MEV breeders; Arabomber and Bomber Exploder adjusted for stun duration and immunity.

MEV:

    Grunt Variants: All added.
        Red: Takes 50% explosion damage, 35% fire damage.
        Cyan: Takes 50% frost damage, 35% electrical damage.
        Yellow: Takes 40% corrosive damage, 40% poison damage.
        White: Time dilated to 1.5x; Scale decreased to 0.5x.
        All can promote into veterans of their own color or grunts of other colors.
        Red and Yellow can promote into Red Praetorian; White and Cyan can promote into Cyan Praetorian.
    Exploders: Added as small veterans of normal exploder.
    White Exploder: Replaces swarmers from normal nexus.
    Macteras: All variants added as a single random choice per mission; can promote into small veterans of their respective color.
    Trijaws: Added as a single random choice per mission.
    Patrol Bots: Added as small veterans of caretaker's patrol bot.

Nexus Variants:

    Red Nexus: Spawns turbomenaces.
    Purple Nexus: Spawns stalkers.
        Stalkers: Take 2x more damage; time dilated to 0.9x; immune to fear and stun.
    Green Nexus: Spawns poison brundles.
    Yellow Nexus: Spawns stingtails.
        Stingtails: Immune to stun and fear; take 4x more damage; time dilated to 2x.

Breeders:

    Green Breeder: Spawns DEA stabber vines.
    Yellow Breeder: Spawns shredders; added as stationary and respawnable.
    Red Breeder: Spawns invisible exploders; time dilated 2x; takes 3x more damage; added as respawnable.
    Purple Breeder: Added as stationary and respawnable; spawns web spitters (variant chosen randomly each mission).

Swarmer Variants:

    Added as large veterans of normal swarmer.

Praetorian Variants:

    Red can promote into large veterans of Yellow and Red oppressors.
    Cyan can promote into large veterans of Cyan and White oppressors.

Oppressor Variants:

    Red Oppressor: Takes 45% damage (50% from kinetic, 75% from fire); scaled up 1.5x; movement speed decreased to 90%; acceleration and deceleration increased to 5x; turn speed increased to 2.5x.
    White Oppressor: Takes 2x more damage, 1.6x more melee damage; time dilated 2x; scaled down to 0.75x.
    Cyan Oppressor: Melee only; invisible.
    Yellow Oppressor: Time dilated 1.5x; takes 2.5x more damage from fire, ice, poison, and corrosion; ignited spreads heat 15m around itself.

Bulks:

    Big Bulk: Scaled up 1.5x; movement speed at 40%; takes 75% from all damage sources, 25% from piercing.
    Black Bulk: Takes 10% from kinetic, explosive, internal damage; 1% from piercing; 150% from fire; 600% from poison, corrosive, electrical damage; 800% from radiation, cold damage; 5x damage multiplier when frozen.
    White Bulk: Takes 10% from elemental damage; 155% from kinetic; 150% from kinetic; 125% from piercing, internal.
    Minibulks: Base HP is 200; time dilated 1.2x; invisible.
    Ice Bulk: Scaled 0.9x; time dilated 1.1x.
    Plantonator: Takes 11x damage from all sources; time dilated 5x; spawns minibulks on death.

Korlok Sprouts: Added.

Nukeballers:

    Added single shot, triple shot, and penta shot to stationary pool; deca shot added in encounters.

Younglings & Shellbacks:

    Cyan youngling can promote into purple and cyan shellbacks as large veterans.
    Red youngling can promote into red and white shellbacks as large veterans.

Leeches:

    Both variants added; silent variant is slow but can grab from nearly anywhere; invisible variant is fast with a small range.

*:
Only in teams, Doesnt spawn in escort/refinery