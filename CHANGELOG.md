# Changelog

# Current Release
## v7 (WIP)
* The Sacrifice
	* Map 1
		* Fixed intro spawn locations not being used by the L4D2 due to a missing function
		* Fixed scavenge spawn positions being incorrect due to the addon that combines The Passing and The Sacrifice causing L4D2 survivors to be used.
		> **Developer Note:** Scavenge configs need to add this fix to their scavenge Stripper:Source configs
	* Map 2
		* Fixed scavenge spawn positions being incorrect due to the addon that combines The Passing and The Sacrifice causing L4D2 survivors to be used.
		> **Developer Note:** Scavenge configs need to add this fix to their scavenge Stripper:Source configs

***

# Past Releases
## v6 (2021-04-05)
* Dead Center
	* Map 1
		* Reverted distance to 400, from 500
	* Map 2
		* Reverted distance to 600, from 700
		* Blocked tank from spawning between 49% - 55%
			* Ban range starts just before the one way drop, and ends by the first set of stairs to get above the street
		* Added fences to the small platform with a tree up the stairs before the walkway
			* Removed blocker on this platform and removed the added foliage
		* Moved the police car by the one way drop further down the street
* Dark Carnival
	* Map 1
		* Replaced added rocks on island before final hill with a shrub wall
	* Map 4
		* Added a porta potty by hedges after bumper cars
		* Adjusted position of added forklift to be easier to use
		* Adjusted position of ammo pile after the bumper cars
		* Added an ammo pile on the picnic tables outside the barn
		* Blocked survivors from standing on top of the scaffolding at the event
		* Added an infected ladder on back of the scaffolding at the event
* Hard Rain
	* Map 1
		* Fixed issues with hittable physics near the generator by the burger tank
	* Map 2
		* Improved clipping on fences throughout the map
	* Map 3
		* Improved clipping on fences throughout the map
	* Map 5
		* Fixed issues with hittable physics near the generator by the burger tank
* The Parish 2
	* Map 2
		* Fixed event horde not resuming if tank is kicked (Thanks ProdigySim and Icy Inferno)
		* Removed 3 (out of 4) pill spawns by the humvee outside saferoom
		* Removed pill spawn behind porta potties outside the saferoom
	* Map 3
		* Removed 2 pill spawns outside the saferoom
		* Removed 1 pill spawn from the dark room under the bus drop, where 2 sets could spawn together

## v5 (2021-03-26)
* Dead Center
	* Map 1
		* Added a fireaxe to the saferoom stairwell
		* Added a set of T1 weapons to the room by the elevator
	* Map 2
		* Added an infected ladder to get over the bus after the event
		* Added an infected ladder to get over the fence by porta potties after the event
* Dark Carnival
	* Map 3
		* Fixed being unable to revive players standing on the jesus spot on the coaster due to the damage type from the barbed wire interupting the pickup
* Swamp Fever
	* Map 1
		* Reworked the added one way drop at the town entrance
		> **Developer Note:** The one way drop's original design proved to be far more deadly than it was ever intended to be. The drop has been redesigned to make it safer and less of a major chokepoint.
* The Parish
	* Map 2
		* Fixed mob timer not being reset when tank is killed
		* Event mob timer is reset when tank spawns to make sure horde stops equally quickly for both teams
* The Passing
	* Map 2
		* Reverted event back to an infinite event
		* Removed barricades on the plank crossing section fire escape, and removed boxes inside Jones & Sons building
		* Repositioned barricades on the alternative route to the plank crossing, added plywood to parts of the barricades, adjusted relevant clipping and ladders
		> **Developer Note:** The barricades on the fire escape were causing confusion and discouraged players from using the original route entirely, as well as extending an already long map. To compensate, the alternative route has also been made shorter, no longer forcing survivors to the top floor.
* The Sacrifice
	* Map 2
		* Removed slow movement trigger in water after barge that Valve forgot to remove from the L4D2 port
		* Re-enabled slowdown on the gravel pile event
		> **Developer Note:** Slowdown was removed as an experiment because existing tools did not provide any way to control the amount survivors were slowed, instead the game forces survivors to move at walking speed. This resulted in too big of a nerf to this chokepoint.<br>Plugin development is now in progress to control the amount of slowdown on the hill, which will allow the original idea of reducing the amount of slowdown to be achieved

## v4 (2021-03-21)
* All Maps
	* Replaced exploitable door model that can be found in the Hard Rain gas station with the damaged version which can't be climbed on
	* Removed additional infected clip type
* Dark Carnival
	* Map 1
		* Blocked survivors from being able to spawn tanks early and get extra distance by jumping at a fence near the pool
		* Added props to visualize ladders between motel balconies
		* Fixed an issue with clipping on added concrete blocks at the end of the map
		* Added ammo pile in lower motel room before the one way drop
		* Extended ladder before one way drop to reach the motel roof and assisted with reaching balcony and other side of roof
		* Added an additional ladder to get on the motel roof by the one way drop
		* Added rocks at the top of the one way drop
	* Map 2
		* Added an infected ladder to climb on the tents above the button to start the event
	* Map 3
		* Reverted tank ban range to 56% - 100%, from 58% - 100%, as late tanks were not spawning due to a bug, and not the ban range
		* Blocked climbing on an outside section of the coaster before the tunnel
	* Map 4
		* Blocked survivors from standing on the shrub walls next to the barn
* Hard Rain
	* Map 1
		* Changed distance points to 400, from 500
	* Maps 2 & 3
		* Added additional clipping to a debris pile players could still get stuck on
		* Moved position of added survivor ladder on the back of the gas station to a more useful location
	* Map 4
		* Changed distance points to 400, from 500
* The Parish
	* Map 1
		* Added an infected ladder to get from the lower section of roof to the upper section on the left of the saferoom
	* Map 2
		* Distance reverted to 500 (default)
		* Event horde will now always stop during tank, resuming once the tank is killed (thanks to NF and Daroot Leafstorm for their help)
		* Limited maximum queued horde during event to stop excessive amounts of horde spawning after the event is stopped
		* Added additional infected ladder to hedge by blocked off route on the left side of the park entrance
	* Map 3
		* Distance reverted to 600 (default)
		* Removed added foliage in open area near the start
		* Added a truck and trailer to the bridge by the ambulance
		* Added clipping to wrecked car at the back end of the bridge to stop players getting stuck on the tires
	* Map 4
		* Reverted tank ban range to 80% - 100%, from 82% - 100%, as late tanks were not spawning due to a bug, and not the ban range
* No Mercy
	* Map 1
		* Reset scoring to Zonemod values until work on these campaigns is ready for public release
* Blood Harvest
	* Map 3
		* Reset scoring and tank ban range to Zonemod values until work on these campaigns is ready for public release
	* Map 4
		* Reset scoring and tank ban range to Zonemod values until work on these campaigns is ready for public release
* Templates
	* Added template for func_nav_blocker and trigger brushes

## v3 (2021-02-26)
* Initial release
    * Swamp Fever
* All Maps
	* Replaced all prop_physics_multiplayer with prop_physics (fixes custom campaigns ignoring prop fixes)
	* Fixed added single pickup weapons being movable before they have been picked up, to prevent griefing
	* Removed additional soundscape entities
	* Removed microphone / speaker effects
	* Fixed fire extinguishers falling off walls
	* Prevented hittables from fading out over far distances
	* Converted all T2 static weapon spawns to T1 weapon_spawn entities
* Dead Center
	* Map 1
		* Replaced the "pill bin" by the elevator that was filtered out by prop fixes
		* Removed fire sounds from the start of the map that can sometimes loop forever and play across the entire map
		* Added LOS blockers under added snack machines
		* Removed fire and building collapse sounds after the elevator
		* Removed scripted zombie spawns that fall through the windows at the end saferoom
		* Slightly reduced the fog strength on the ground floor
		* Blocked survivors from standing on the awning above the check-in desk
	* Map 2
		* Removed the police car at the bottom of the first ramp (which was previously moved to the other end of the street)
		* Added a fence cover by the dumpster drop
		* Enabled the 2 alarm cars after the event
		* Added LOS blockers to added props after the event
		* Added boxes to the walkway before the gun store
		* Added a billboard by the walkway before the gun store
	* Map 3
		* Made the event infinite again
		* Added guareneteed shotgun and SMG spawns to the back corner before the event path
		* Added a clip to make the jump back up the one way drop slightly easier
		* Moved the hand truck at the start of the event path to a less obtrusive position
		* Added an ammo pile on the boxes after the stairs on the event path
	* Map 4
		* Blocked gas cans from being launched by infected onto the 4th floor, and behind the walls on the 3rd floor corner cans
		* Removed a left over clip from testing that was left in accidently
		* Fixed spit block not covering the entire elevator
* Dark Carnival
	* Map 1
		* Adjusted position of added rocks before the final hill
	* Map 2
		* Improved clipping on the sign above saferoom and by the peanut gallery
		* Adjusted angle of added foodcart and ladder to fix collision issues
		* Moved the added magnum spawn in the new area closer to the entrance and made it potentially spawn a pistol or magnum
		* Added clipping to the bottom of the slide to prevent extreme ice-like movement
		* Replaced the added fences by the slide with a vending machine and boxes
		* Adjusted color of added hedge near the end of the map
	* Map 3
		* Added non-solid poles to indicate where exploit block clips on the first ramp are
		* Added a damage trigger to discourage using a jesus spot on the right fence at the first ramp, indicated by razor wire
			* Damage will only occur when a survivor is standing on the razor wire for a few seconds, building up to deal 1 damage every 0.5 seconds (minimum possible amount)
	* Map 4
		* Replaced the 2 bumper cars in the saferoom with a single bumper car
		* Added teleport triggers for survivors that get stuck inside props added to the saferoom
		* Improved game hut sign clipping
		* Moved added ammo pile after bumper cars and changed its model to make it more visible
		* Replaced the added plywood at the event to fix common infected nav issues
* The Parish
	* Map 1
		* Added missing glass to wrecked car
	* Map 2
		* Added clipping to improve the usage of the ladder on the tree by the gazebo
		* Fixed getting stuck at the top of some ladders added to the hedges for the park route rework
		* Added an ammo pile by the event button
	* Map 3
		* Made the guns in the first house always spawn a shotgun and SMG
		* Extended the wall by the cemetery entrance
		* Added infected ladders to the added crypt that blocks the path in the cemetery
	* Map 4
		* Removed the added pool table in the pool room
		* Adjusted the position of the added ammo pile at the event to be more visible
* The Passifice / The Saccing
	* Map 1
		* Disabled the added alarm car at the start of the map
	* Updated `thesaccing.vpk` to `thesaccing_v2.vpk`, which combines The Passing and The Sacrifice campaigns:
		* Uses the updated mission files from the Last Stand update
		* Fixes The Sacrifice map 1 tank not using the unique tank arms model
		* After The Sacrifice finale ends, the map will change back to The Passing for the scavenge finale if players wish to play it
		* Supports spawning of all melee weapons that are available in both campaigns
> Server owners can remove the original `addons/thesaccing.vpk` file from their servers and replace it with this new version
* Templates
    * Added hittable prop template
* SourceMod
	* Added 2 new files to replace cvars in `shared_settings.cfg` globally:
		* `cfgogl/boss_spawns.cfg` - Defines boss spawns for specified maps to control flow or finale tank spawns
		* `cfgogl/spit_block.cfg` - Defines regions where spit does not deal damage to survivors
		* Simply replace the relevant sections in your config's shared_settings.cfg file with:
			* `exec cfgogl/boss_spawns`
			* `exec cfgogl/spit_block`
			* For configs that want to use different settings, add a copy of these files to your config's folder and load them through the same method in the `shared_settings.cfg` file with the corrected file path

## v2 (2021-01-18)
* Initial release
    * The Passing
    * The Sacrifice
* Dark Carnival
    * c2m2: Fixed added dumpster from spawning inside the floor
* Swamp Fever
    * c3m1: Removed some floating oil barrels
* The Parish
    * c5m3: Removed the blue coloring on disabled alarm cars (temporarily)
	* c5m4: Blocked standing on the edge of the garage roof on the first street
	* c5m4: Blocked standing on the edge of the electrical box after the pool room
* Added a failsafe for fading out alarms to ensure they don't start playing again
* Added `point_nav_attribute_region` to `entity_template.cfg`

## v1 (2021-01-03)
* Initial release
    * Global Fixes
	* Dead Center
	* Dark Carnival
	* Hard Rain
	* The Parish