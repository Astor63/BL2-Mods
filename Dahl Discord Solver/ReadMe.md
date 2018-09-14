## Discord Solver (Lascaux & Moxxi Version)

In their early days in their making of weapons, Dahl, in collaboration with Torgue created the Discord Solver, a SMG who shot GyroJet explosive bullet. 

Unfortunately, the agreement between the two weapons manufacturers did not last long, and the production of the SMG stopped quickly -How ironic for a weapon that's named Discord Solver!- and Torgue seized the patents to create the Pocket Rocket.

It would seem that Moxxi still has a specimen of the Discord Solver in her private Signature collection of weapons, but no one has ever seen it, not even Marcus ... so maybe it's just a legend after all?

Anyway, remnant of the past, a *"lost"* Discord Solver (probably dropped by a bandit?) can still be found... submerged in a shallow pool in Frostburn Canyon.

This is where you can find it... 

![Discord Solver - Where to find it](https://i.imgur.com/uHTxuc6.png "Don't worry guys... even if my screen capture show French text, my mods are in English")

## What special with this weapon?

- Both Version:
  - Keep (almost) of all his Unique weapon specificity: very high firerate, variable burst-fire round, shot two bullets for the cost of one ammo, etc... for more details, see [Borderlands Wiki](http://borderlands.wikia.com/wiki/Lascaux) 
  - Initial damage reduced by 20%, but...
    - FireMode modified to shoot GyroJet Explosive bullet. 
	- Shot two GyroJet explosive bullet for the cost of one ammo (can be doubled if you use the Aaron00000's "Double Anarchy" mod).
    - Impact Explosion boosted by Grenade Damage. 
- Moxxi Version:
  - As usual for the Vanilla Moxxi weapons, this Moxxi SMG will give you the benefice of 70% Critical hit bonus and 2.5% lifesteal on damage dealt.
  
Not clear? ... Well, perhaps it will be more easy to compare the difference in a table:  
  
| Tech Specs      | Lascaux: Vanilla      | Discord Solver #1: Lascaux  | Discord Solver #2: Moxxi  | 
| -------------   | -------------         | -------------               | -------------             | 
| Bullet:         | Standard              | GyroJets                    | GyroJets                  | 
| Burst Count:    | 9 to 14 rounds        | 9 to 14 rounds              | 9 to 14 rounds            | 
| Critical Hit:   | None                  | None                        | 70%                       | 
| Element:        | Never Elemental       | Never Elemental             | Never Elemental           | 
| Element Chance: | None                  | None                        | None                      | 
| Fire Cost:      | 2 bullets cost 1 ammo | 2 bullets cost 1 ammo       | 2 bullets cost 1 ammo     | 
| Lifesteal:      | N/A                   | N/A                         | 2.5% of damage dealt      | 
| Skin:           | Lascaux (Vanilla)     | Lascaux (Vanilla)           | Moxxi Signature           | 
| Rarity:         | Unique                | Unique                      | Moxxi                     | 
  
  
![Discord Solver - Lascaux vs Moxxi Version](https://i.imgur.com/ySWyM5T.png "Don't worry guys... even if my screen capture show French text, my mods are in English")

**Note:** As the Discord Solver can be found submerged in a shallow pool in a cave, it's make sense to me to keep his Vanilla "Lascaux" skin (similar to the Lascaux cave paintings), but the Moxxi version, she get a ~~vivid red~~ ... gorgeous Moxxi Signature skin.

### Options: 

This Mod has few options & fix, so feel free to use the BLCMM tool to select the best option that suit you.

- Both Version:
  - The Bullet Speed Mode has a toggle option between Normal/Double/Triple Speed
  - The Firing Mode has a toggle option between Pocket Rocket or GyroJet explosive bullet (see Compatibility below)
  - The Explosion Impact Type has a toggle option between Explosive/Explosive ForceFlinch/None
  - The Splash Format has a toggle option between Grenade/Rocket/Reaper (see Compatibility below)
  - The Weapon Card has a toggle option between Show/Hide the additional informations.
- Moxxi Version:  
  - The Moxxi's Lifesteal can be toggle between the "Classic" instant healing or with Orb Transfusion (similar to the SR Chère-Amie)
  - The Discord Solver Moxxi Version can become the reward given by Moxxi for the mission "Hell Hath No Fury" in Opportunity (see picture below)... on this way you can pick up your 1st Discord Sover in Frostburn Canyon (Level 7-10) and get another one as Mission Reward (Level 25-30) in Opportunity.

... and few fix:

- Both Version:
  - Fix for Orudeon's "Bayonet Enhancements" (Bayonet in slot 2)
  - Fix for Orudeon's "Bayonet Enhancements" (Bayonet in slot 2) + Bayonet Buff
  - Fix for Koby "Rarity Color Fix": Unique or Moxxi (just in case if you use this old mod)
- Moxxi Version:
  - Fix for Akathis "No More Moxxi Lifesteal" - 1.5% passive health regeneration instead of 2.5% Lifesteal
  
![Discord Solver as reward for Moxxi mission](https://i.imgur.com/8JPt8ap.png "Don't worry guys... even if my screen capture show French text, my mods are in English") 

**Note:** You can toggle between the choice from 2 Moxxi Discord Solver or between the choice from 1 Moxxi Discord Solver & 1 Kiss of Death. 

### Compatibility:

- 100% compatible with [UCP Patch](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Community%20Patch%20Team)

- Should be compatible with most other mods, as long as they do not modify the Pocket Rocket Firing Mode.

- Just be aware from the following:

  - To be sure to get the fix Orudeon's Bayonet Enhancements and/or Orudeon's Bayonet Buff working correctly (as intended), don't forget to place my mod **AFTER** Orudeon's Bayonet Enhancements & Bayonet Buff. 
 
  - This Mod **KEEP** the specific burst from the Lascaux, so if you use the Bandit Brand Tweaks v1.2 by Orudeon, there is a option that reduce the burst to five-shot bursts.  To get back the specific burst, just open your Orudeon's Bandit Brand Tweaks folder, go to: *SMG/Burst Count/* (if you use the Gears Overhaul Orudeon's Mod v1.35, the path will be: *Brands Tweaks/Bandit Brand Tweaks v1.2 by Orudeon/SMG/Burst Count/*) and uncheck the following line:  
  ```
  [ ] set GD_Weap_SMG.Barrel.SMG_Barrel_Bandit_Lascaux ZoomWeaponAttributeEffects ((AttributeToModify = AttributeDefinition'D_Attributes.Weapon.WeaponAutomaticBurstCount',ModifierType = MT_PreAdd,BaseModifierValue = (BaseValueConstant = 1.000000, BaseValueAttribute = None, InitializationDefinition = None, BaseValueScaleConstant = 1.000000)))
  ``` 
  - This mod use the Pocket Rocket Firing Mode, so if you use any mode that changes the attributes from the Pocket Rocket, it will affect this mod, and obviously the firing of the Discord Solver. In this case, Just revert the modification done previously to the Pocket Rocket.
  
  - This mode use Grenade Damage for the Splash Format, so if you are going to use the Discord Solver with a Siren character :warning: Maya :warning: , don't forget to toggle the Grenade Damage to Reaper Splash Damage.
  
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
  
### Other Recommended Mods:

A great mod to check for the Discord Solver:

- Moxxi Version: [No More Moxxi Lifesteal v2.0](https://github.com/BLCM/BLCMods/blob/master/Borderlands%202%20mods/Akathris/NoMoreMoxxiLifestealv2.0.txt) by [Akathris](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Akathris) . His Mod is self explanatory: removes lifesteal from Moxxi weapons and changes it to passive health regeneration.

- Both Version: [Double Anarchy v4](https://github.com/BLCM/BLCMods/blob/master/Borderlands%202%20mods/Aaron0000/Weapon-Item%20Parts%20and%20Accessories/DoubleAnarchyv4.txt) by [Aaron00000](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Aaron0000) : Changes the SMGs accuracy accessory into the Double Accessory from Borderlands 1... and your Discord Solver will shot 4 bullets/projectiles at the cost on 2 ammo.

![Discord Solver Lascaux Version with Double Anarchy Mod](https://i.imgur.com/fkJRAqD.png "Don't worry guys... even if my screen capture show French text, my mods are in English")  
  
### Credits & Thanks:

I find a lot of useful informations on the Resource page from the [Wiki](https://github.com/BLCM/BLCMods/wiki) of course, but also on the [Resources page](https://github.com/BLCM/BLCMods/tree/af3b2d17629ab3f7f7a5f7bb68b489c5e13b0498/Borderlands%202%20mods/Dave/Resources) and the great [Dave'S BL2 Skin Modding Guide](https://cdn.rawgit.com/BLCM/BLCMods/bb1933f7/Borderlands%202%20mods/Dave/DAVE%27S%20BL2%20SKIN%20MODDING%20GUIDE.pdf) ... all that made by [Dave](https://github.com/BLCM/BLCMods/tree/af3b2d17629ab3f7f7a5f7bb68b489c5e13b0498/Borderlands%202%20mods/Dave) , so thanks for your work, @DaveRabbit 

Oh! I almost forget... I also follow step-by-step this [How to make a modded weapon](https://github.com/BLCM/BLCMods/blob/master/Borderlands%202%20mods/Tsunami-s%20Guns%20Cannons%20And%20Flamethrowers/(((How%20to%20make%20a%20modded%20weapon))).txt) guide writing by [Tsunami](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Tsunami-s%20Guns%20Cannons%20And%20Flamethrowers) , thanks to you too, @Tsunami7900  

### Note: 

Any critique would be appreciated because I am new in weapon modding... and by the way, please leave constructive criticism if you make a video. 
Enjoy!

### Disclaimer

All files and content provided here were written by me (Astor), unless stated otherwise.

- They are free for personal use. You may use these mods in videos, or for streaming, as long as you give me proper credit. I would appreciate that you'll letting me know about it, and at least, provide a link to [Github.com/BLCM/BLCMods/Borderlands 2 mods/Astor](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Astor) .

- You may re-use small bits of code (e.g. formulas, behavior modifications, etc) for your own purposes, and let me know about it. 

- Ask me for permission first if you wish to use larger portions of this code, make a modified/improved version, include it in a mod pack, etc..., and don't forget to provide credit.

- Do not re-upload this mod or any of my mods anywhere without my explicit permission... ANYWHERE!

* * * * *
