# Let Me Climb That!
### A mod for getting on top of high places
#### *By ArmoredThirteen*


## Description
Todo lol


## Installation
Add files to Data folder or use mod manager.
Todo, could be more descriptive, never know if this is someone's first...


## Change log
#### 0.1: Initial build
- Added DJ Lasers' shop to shack near Yangtze Memorial
	- Changed name of Wilderness at (-13,1) to ATEDJLasersShop
	- Placed store on top of shack
	- Modified relevant nav meshes
- Created DJ Lasers NPC
	- Merchant with limited stock of energy weapons
	- New dialogue to allow vendoring and provide backstory
- New cigarette and tin can static objects, using existing models
	- ATECigarette01Static
	- ATETinCan[01/02]Static
#### 0.2: Camp Golf
- 2CCampGolfResort (interior)
	- Added door in front of stair rubble that leads to rooftop
	- Modified navmesh to not go past new door
- Added full fortifications to resort's rooftop
	- Cells changed: (7,16), (7,17), (8,16), (8,17)
	- 4 guard towers with fortified lower area, one on each corner
	- 12 troopers working in 4 groups of 3 shifts
		- Guard tower, patrol lower fortification, and sleep
	- 2 patrolling heavy troopers and 1 wandering
	- Basic sleeping tent
	- Ammo and food tent
	- Small radio tower with generator
- New objects
	- NPCs to handle patrols and a few generic purpose ones
		- ATENCRHeavyTrooper[Guard/Patrol/Wander][''/F/M/Var]
		- ATECampGolfNCRTrooperRoof[1-4][A-C]
	- Packages to control rotating schedules
		- ATECampGolfRoof[1-4][A-C][Guard/Patrol/Sleep]
	- ATELootAmmoBoxGrenadeLock: Grenade box with more and better grenades
	- ATENCRHeavyTrooperWeaponsIncinMini: Weapon list that only allows incinerators and miniguns
#### 0.3: Freeside, Rooftop Farm
- Added Slurps' farm to rooftop near Freeside Water Pump
	- Fire escape that goes to roof
	- Pickable corn and potatoes
	- Very pleasant picket fence and compost pile
- New objects
	- ATESlurps: Farmer ghoul
	- ATEPotatoStatic: Static object using potato model
	- ATEPotatoPickable: Activator for harvesting potatoes. Uses jalapeno plant model.
	- ATEPotatoPickableScript: Script for ATEPotatoPickable to harvest 1-3 potatoes
	- ATESCOLDirtBucket: Bucket with dirt piles to appear filled with dirt, static collection
	- ATESCOLDirtPot: Pot with dirt piles to appear filled with dirt, static collection
	- ATESCOLWoodCartDirtSmall: Small wood cart with dirt piles to appear filled with dirt, static collection
	- ATESCOLWoodSpoolPost: Wooden spool with wood rod sticking out one side, static collection
	- ATEEffectPotatoMush: Spell effect with +1 str, -2 int, -35 dehydration
	- ATEWaterTypePotatoMush: Water type using EffectPotatoMush so it can be drunk direct from sources
	- ATEPotatoMushScript: Script that adds the ATEEffectPotatoMush to the player on activate
	- ATEPotatoMushMachine: Activator that uses ATEPotatoMushScript and the mesh for IndustrialMachine11