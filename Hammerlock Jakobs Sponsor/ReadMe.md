## Hammerlock Jakobs Sponsor

### What do this mod?

- The 10 missions given by Hammerlock in the main game will be rewarded with a Jakobs weapon/item
  - In the Mission Bad Hair Day (Southern Shelf) the Hammerlock reward is now a Blue Sniper Jakobs or a Blue Shotgun Torgue (if the fur is given to Clap-Trap).
  - The reward for the other missions given by Hammerlock are now rewarded by a Blue Jakobs weapon/item: 
    - Handsome Jack Here! (Southern Shelf)
    - Mighty Morphin' (Tundra Express)
    - Perfectly Peaceful (Caustic Caverns)   
    - Shielded Favors (Southern Shelf)
    - Stalker of Stalkers (The Highlands)
    - Symbiosis (Southern Shelf)	  
    - The Name Game (Three Horns - Divide)	  
    - This Town Ain't Big Enough (Southern Shelf)
  	
![Jakobs pistol as reward for Handsome Jack Here! in Southern Shelf](https://i.imgur.com/1TWYXxs.png "Don't worry guys... even if my screen capture show French text, my mods are in English")
	
_**Note:** As for my Double Quest Reward "Redux", this Mod will give you the choice between 2 weapons/items instead of a single one, so it will double the chance to get a weapon/item with desired parts._	

### Changelog:

- v1.0.0, September 2, 2018
  - Initial public release
 
- v1.0.1, September 5, 2018
  - Added Stalker of Stalkers in The Highlands... Ooops! I totally forget this mission... perhaps because the "Turn In" is done in a letter box in Overlook!
  
### Compatibility:

- 100% compatible with UCP 4.1
- Should be compatible with most other mods, as long as they do not touch the Quest Reward.
- This mod was tested:
  - Stand alone 
  - With [UCP Patch](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Community%20Patch%20Team)  
  - With [UCP Patch](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Community%20Patch%20Team)  & [Better Quest](https://github.com/BLCM/BLCMods/blob/master/Borderlands%202%20mods/Hemaxhu/Quest%20Rewards/Better%20Quests) by [Hemaxu](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Hemaxhu) .
  - With [UCP Patch](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Community%20Patch%20Team)  & [Better Loot](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Apocalyptech/BL2%20Better%20Loot%20Mod) by [Apocalyptech](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Apocalyptech)
  - With [UCP Patch](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Community%20Patch%20Team)  & [Cold Dead Hands](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Apocalyptech/BL2%20Cold%20Dead%20Hands) by [Apocalyptech](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Apocalyptech)

To be sure to get this mod working correctly (as intended), don't forget to place it **AFTER** UCP 4.1 and Better Quest (Better Loot & Cold Dead Hands can be placed anywhere regarding my mod). 

### Troubleshooting:

If a option or a fix don't work as intended, it's not because the Mod is not well coded, but probably (read: in 90% of cases) because this option is overwritten by another mod.

#### What's go wrong?

It's simply because 2 commands work on the same parameter, and one is overwritten by the other.

Better to explain that with a exemple, isn't?

Let's take 2 of my mods:

1.  The *Double Quest Rewards*, which give the choice between 2 *Kiss of Death* given by Moxxi for the mission *Hell Hath No Fury*.  
 
2. The option in *SMG Dahl Discord Solver - Moxxi Edition*, which give the choice betwen 2 *SMG Dahl Discord Solver - Moxxi Edition* given by Moxxi for the mission *Hell Hath No Fury*. 

You activate the option to have the choice between 2 *SMG Dahl Discord Solver - Moxxi Edition* given by Moxxi for the mission *Hell Hath No Fury*, but you still receive the choice from 2 *Kiss of Death* instead of the choice beteen 2 *SMG Dahl Discord Solver* as desired.

Left picture: The mod *SMG Dahl Discord Solver - Moxxi Edition* is placed **BEFORE** the Mod *Double Quest Rewards*, and the option which give the choice betwen 2 *SMG Dahl Discord Solver - Moxxi Edition* appear in *Dark Green*, that's mean, that another bunch of code overwrite this command (in this case the choice from 2 *Kiss of Death* from the Mod *Double Quest Rewards*)... and yes, that's don't work.

Right picture: To fix this overwriting problem and get the code working as intended, the mod *SMG Dahl Discord Solver - Moxxi Edition* must be moved **AFTER** *Double Quest Rewards*. Once done, the reward will appear in *Light Green*, meaning that the code will work correctly, and you will have the choice betwen 2 *SMG Dahl Discord Solver - Moxxi Edition* for the mission *Hell Hath No Fury*
![Fix or option not working as intended](https://i.imgur.com/a0eZEVB.png "Don't worry guys... even if my screen capture show French text, my mods are in English")
To summarize: Dark Green = don't work (is overwritten) / Light Green = work (overwrite)... by moving the mod at the end of your patch, the problem will be solved. 

### To do:

- [x] Check twice if I don't forget a Hammerlock mission somewhere (again).
- [ ] Make (again) a new playthrough to be sure that all the rewards are given correctly.
- [ ] Clean the code and remove all my ~~shitty~~ notes.

### Credits & Thanks:

I find a lot of useful informations on the Resource page from the [Wiki](https://github.com/BLCM/BLCMods/wiki) of course, but also all the Mission Names and Mission Objectives on the [Resources page](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/FromDarkHell/Resources) from [FromDarkHell](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/FromDarkHell) , so thanks for your work, @FromDarkHell 

### Disclaimer

All files and content provided here were written by me (Astor), unless stated otherwise.

- They are free for personal use. You may use these mods in videos, or for streaming, as long as you give me proper credit. I would appreciate that you'll letting me know about it, and at least, provide a link to [Github.com/BLCM/BLCMods/Borderlands 2 mods/Astor](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Astor) .

- You may re-use small bits of code (e.g. formulas, behavior modifications, etc) for your own purposes, and let me know about it.
 
- Ask me for permission first if you wish to use larger portions of this code, make a modified/improved version, include it in a mod pack, etc..., and don't forget to provide credit.

- Do not re-upload this mod or any of my mods anywhere without my explicit permission... ANYWHERE!

* * * * *
