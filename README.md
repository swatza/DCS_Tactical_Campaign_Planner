# DCS_Tactical_Campaign_Planner
An automated script/campaign manager that is designed to make more interesting mission scenarios for you and your friends to perform operations on and automate the campaign experience.

This is a new project being started in Summer of 2021 to create more interesting Close-Air-Support type operations with the intent to create non-static targets, responsive AI, and interesting / hidden missions to challenge the players. 

Purpose
--------
Create tactical mission scenarios of allied and opposition forces that add immersions to the DCS flight experience without needing to construct everything by hand. 
In this usecase, a campaign is a series of contextualized scenarios that build upon the previous to define a win and lose condition. Each mission could be considered as a single set of flights (operations) or a window time for the players to execute a series of flights during.  

Use
--------
Generation of new Campagin
* Determine 'Campaign' Type 
* Choose a Map 
* Choose the Region
* Decide on Faction (Red or Blue) and faction participants
* Determine Size of Operation
* Modify/Edit operational forces of both sides
* Select AI Behavior and Difficulty
* Edit Flights and Player Settings
* Generate the first mission and briefings

In between missions
* Save results screen from post mission 
* Record the differences and objectives of each of the units. 
* Create the next mission

Phases
--------
Phase 1: DCS Mission Planning Integration
- Spawn a unit at a given location 
- Assign a unit a set of waypoints
- Assign a unit a trigger
Phase 2: External Campaign Editor
- UI and battle force designer
- Force Composition pre-sets
- Campaign and Map selection
- Battleforce AI for planning
- Data management of battleforces
Phase 3: Post Mission Report
- Calculating mission results
- Planning/adjusting AI behavior
Stretch Goals
- Runtime Integration with responsive AI replanning


Design Details
-------
WIP
Campaigns: Frontline & Invasion/Strike
* Frontline - Symmetric mode with two opposing forces have their forward lines of troops trying to engage, capture territory and defeat the opposing force in a near head on head competition.
* Invasion/Strike - Asymetric mode with one force acting as the attacker and one as the defender trying to secure a main objective and several secondary objectives.

