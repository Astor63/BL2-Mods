
## Finesse (Commerce & Moxxi Version)

In their early days in their making of weapons, Hyperion, seized Alien Technology plans and created the Finesse: a Plasma Caster who fire SEAPP (Smart Elemental Adaptive Plasma Projectile). 

Unfortunately, the mastery of this Alien technology was in its infancy, and atrociously expensive, which made the price of sale of these weapons totally prohibitive, and therefore unavailable to the majority of bandits, which involved the production stoppage of this revolutionary Plasma Caster only after a few (rare) copies sold.


It would seem that Moxxi still has a specimen of the Finesse in her private Signature collection of weapons, but no one has ever seen it, not even Marcus ... so maybe it's just a legend after all?

## What special with this weapon?

- Both Version:
  - Use SEAPP (Smart Elemental Adaptive Plasma Projectile): a Alien Plasma Projectile which adapt his Elemental following the impact:
    - Incendiary on flesh
    - Shock on shield
    - Corrosive on armor
  - Splash damage booster by grenade  
- Moxxi Version:
  - As usual for the Vanilla Moxxi weapons, this Moxxi SMG will give you the benefice of:
    - 95% Critical hit bonus 
	- 2.5% lifesteal on damage dealt
  
Not clear? ... Well, perhaps it will be more easy to compare the difference in a table:  
  
| Tech Specs        | Commerce: Vanilla     | Finesse #1: Commerce  | Finesse #2: Moxxi     | 
| -------------     | -------------         | -------------         | -------------         | 
| Bullet:           | Standard              | SEAPP                 | SEAPP                 | 
| Burst Count:      | 9 to 14 rounds        | 5 rounds              | 5 rounds              | 
| Critical Hit:     | None                  | None                  | 95%                   | 
| Elemental:        | Shock                 | Elemental Adaptive    | Elemental Adaptive    | 
| Shock dmg/sec:    | Never Elemental       | 3605,9                | 3605,9                | 
| Corrosive dmg/sec:| N/A                   | 3605,9                | 3605,9                |
| Shock dmg/sec:    | 3605.9                | 3605,9                | 3605,9                |
| Elemental Chance: | 11.5%                 | 8%                    | 8%                    | 
| Splash Format:    | None                  | Grenade               | Grenade               | 
| Fire Cost:        | 1 bullets cost 1 ammo | 1 SEAPP cost 1 ammo   | 1 SEAPP cost 1 ammo   | 
| Lifesteal:        | N/A                   | N/A                   | 2.5% of damage dealt  | 
| Skin:             | Commerce (Vanilla)    | Commerce (Vanilla)    | Moxxi Signature       | 
| Rarity:           | Unique                | Legendary             | Moxxi                 | 
  
  
![Discord Solver - Commerce vs Moxxi Version](https://i.imgur.com/ySWyM5T.png "Don't worry guys... even if my screen capture show French text, my mods are in English")

**Note:** As the Finesse can be found submerged in a shallow pool in a cave, it's make sense to me to keep his Vanilla "Commerce" skin (similar to the Commerce cave paintings), but the Moxxi version, she get a ~~vivid red~~ ... gorgeous Moxxi Signature skin.

### Options: 

This Mod has few options & fix, so feel free to use the BLCMM tool to select the best option that suit you.

- Both Version:
  - The Elemental Effect Chance can toggle from 1% to 40%
  - The Plasma Projectile Speed Mode has a toggle option between Normal/Double/Triple Speed
  - The Explosion Impact Type has a toggle option between Explosive/Explosive ForceFlinch/None
  - The Splash Format has a toggle option between Grenade/Rocket/Reaper (see Compatibility below)
  - The working Flaps can be toggle beween On or Off
  - The Weapon Card has a toggle option between Show/Hide the additional informations.
- Moxxi Version:  
  - The Moxxi's Lifesteal can be toggle between the "Classic" instant healing or with Orb Transfusion (similar to the SR Chère-Amie)
  - The Finesse Moxxi Version can become the reward given by Moxxi for the mission "Hell Hath No Fury" in Opportunity (see picture below) 

... and few fix:

- Both Version:
  - Fix for Orudeon's "Bayonet Enhancements" (Bayonet in slot 2)
  - Fix for Koby "Rarity Color Fix": Unique or Moxxi (just in case if you use this old mod)
- Moxxi Version:
  - Fix for Akathis "No More Moxxi Lifesteal" - 1.5% passive health regeneration instead of 2.5% Lifesteal
  
![Finesse as reward for Moxxi mission](https://i.imgur.com/8JPt8ap.png "Don't worry guys... even if my screen capture show French text, my mods are in English") 

**Note:** You can toggle between the choice from 2 Moxxi Finesse or between the choice from 1 Moxxi Finesse & 1 Kiss of Death. 

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

![Finesse Moxxi Version with Double Anarchy Mod](https://i.imgur.com/fkJRAqD.png "Don't worry guys... even if my screen capture show French text, my mods are in English")

### Compatibility:

- 100% compatible with UCP 4.1
- Just be aware from the following: 
      - This mode use Grenade Damage for the Splash Format, so if you are going to use the Discord Solver with a Siren character :warning: Maya :warning: , don't forget to toggle the Grenade Damage to Reaper Splash Damage.
  
### Credits & Thanks:

I find a lot of useful informations on the Ressource page from the [Wiki](https://github.com/BLCM/BLCMods/wiki) of course, but also on the [Resources page](https://github.com/BLCM/BLCMods/tree/af3b2d17629ab3f7f7a5f7bb68b489c5e13b0498/Borderlands%202%20mods/Dave/Resources) and the great [Dave'S BL2 Skin Modding Guide](https://cdn.rawgit.com/BLCM/BLCMods/bb1933f7/Borderlands%202%20mods/Dave/DAVE%27S%20BL2%20SKIN%20MODDING%20GUIDE.pdf) ... all that made by [Dave](https://github.com/BLCM/BLCMods/tree/af3b2d17629ab3f7f7a5f7bb68b489c5e13b0498/Borderlands%202%20mods/Dave) , so thanks for your work, @DaveRabbit 

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
