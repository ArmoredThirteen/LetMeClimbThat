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
	- Added door in front of stair rubble that leads to rooftop.
	- Modified navmesh to not go past new door.
- Added full fortifications to resort's rooftop.
	- Cells changed: (7,16), (7,17), (8,16), (8,17)
	- 4 guard towers with fortified lower area, one on each corner.
	- 12 troopers working in 4 groups of 3 shifts.
		- Guard tower, patrol lower fortification, and sleep.
	- 2 patrolling heavy troopers and 1 wandering.
	- Basic sleeping tent.
	- Ammo and food tent.
	- Small radio tower with generator.
- New objects.
	- NPCs to handle patrols and a few generic purpose ones.
		- ATENCRHeavyTrooper[Guard/Patrol/Wander][''/F/M/Var]
		- ATECampGolfNCRTrooperRoof[1-4][A-C]
	- Packages to control rotating schedules.
		- ATECampGolfRoof[1-4][A-C][Guard/Patrol/Sleep]
	- ATELootAmmoBoxGrenadeLock: Grenade box with more and better grenades.
	- ATENCRHeavyTrooperWeaponsIncinMini: Weapon list that only allows incinerators and miniguns.
