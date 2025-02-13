[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity

Put your notes from the W1L2 (Thurs, Jan 9) in-class activity here.

HW1 Break-Down

Objects:
UI
-Seeds planted shows how many seeds the player has planted
-Seeds remaining shows how many seeds the player has available
Player
-Movement with the WASD keys
-Player can plant plants with space bar
-Planting seeds effects the UI; seeds planted increments while seeds remaining decrements
-The player cannot plant seeds after they have used all of them
-Has a bunny sprite to represent player
-Player can still move even if no seeds remain
Plants
-Has a plant sprite to represent plant
-The plant appears in the front of player layer when planted 
-The plant has no physics or movement, unlike the player


## Devlog
Prompt: Include the HW1 break-down exercise you wrote during the Week 1 - Lecture 2 (Jan 9) in-class activity (above). If you did not attend and perform this activity, review the lecture slides and write your own plan for how you believe HW1 should be built. If your initially proposed plan turned out significantly different than the activity answers given by Prof Reid, you may want to note what was different. Then, write about how the plan you wrote in the break-down connects to the code you wrote. Cite specific class names and method names in the code and GameObjects in your Unity Scene.


Write your Devlog here!

We did end up writing it down, but the fact that  wasn't the first thing that came to mind that the plants spawn at the position of the player. I had to go back and add this when I was making the player script. In the PlantSeed method, I had to pass in the player's position and rotation when I call Instantiate to make the plant spawn in the player's position. Another interesting feature from the list was that the plant appears in front of the player. Someone else in my group wrote that part, but I didn't pay much attention to that until I had already made my game and the plant object spawned behind the player object. I had already made and uploaded a build when I noticed, and was told it won't affect my score, but I wanted to do it just to make sure I knew how and all I had to do was change the order in layer of the plant prefab to be higher ( I just made it 3 to be safe).

When I started making the game, the first thing I thought about was the basic things like "what happens when I press each button" instead of something like immediately trying to implement the methods like UpdateSeeds in PlantCountUI. The first thing I did was make the player move with the wasd keys. Then I moved from there to what happens when you press space which I feel connects to the rest of the features/steps. Like if I start working from just what happens when you press space then I will end up working on adding to seeds planted, subtracting from remaining seeds, changing the UI, instantiating a plant, and where the plant goes.


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
