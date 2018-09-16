**Il est important que tu lises ca dans l'ordre, il y a à la fin 2 vidéos qui montrent ce que j'explique en action.**

### Les Parents
Pour comprendre ce qu'est le **Parent** dans un materiel, il faut comprendre comment marche l'aspect visuel des materiaux.

Comme tu as pu le remarquer, quand on fais un skin, on est pas obligé de mettre **tous** les parametres, si on veut pas changer la couleur secondaire d'une arme, bah on va juste pas mettre BColor dans notre mod.  
Sauf que, BColor existera quand meme, il va pas devenir transparent ou noir. Et ce BColor qu'on a pas touché, il vient donc du **Parent**. Tout les materiaux ont un parent.  

Par exemple, si on prend le materiel du Butcher,  
**Gladiolus_GunMaterials.Materials.Shotgun.Mati_Hyperion_6_SG_Butcher**,  
on peux voir ses parametres en faisant un dump du code ci-dessus (expliquation sur les dump plus bas mais lis dans l'ordre).  
![Image](https://i.imgur.com/zP4gi8O.png)
Le dump nous montre donc que le Butcher n'a que **AColor** de modifié et les 3 impératifs de **TextureParameterValues**.  
On voit aussi qu'il a pour parent :  
**Common_GunMaterials.MasterMaterials.Hyperion.MasterMati_HyperionUncommon**  
Et c'est dans ce "MasterMati_HyperionUncommon" que ce trouve tous les autres parametres, et c'est donc aussi le materiel parent de toutes les armes Hyperion de rareté verte (le nom est assez explicite)  

Si on voulait copier le skin du Butcher sur par exemple, le Creamer, si on ne change pas le parent, le Creamer aura l'apparence de son parent (MasterMati_BanditUncommon) + le rouge pale du Butcher

### Les Dumps
Tout d'abord, je suis très étonné de voir que tu as fais tout ca sans jamais avoir utilisé de dump.  

La commande **obj dump [code]** permet de voir tous les parametres d'un objet quelconque (Ca peut etre un materiel, une pool de loot, le comportement d'une IA, vraiment a peu pres tout).  
Donc par exemple, si je veux reproduire le skin du Butcher sur une autre arme, je fais  
**obj dump Gladiolus_GunMaterials.Materials.Shotgun.Mati_Hyperion_6_SG_Butcher**  
et la je peux voir quels sont les parametres qui font son apparence (TextureParameterValues, Scalar et Vector).  
Heureusement, il existe un autre moyen pour voir et recopier des parametres plutot que de les lire sur la console et les réécrire : l'**object explorer** du **[BLCMM](https://github.com/BLCM/BLCMods/wiki/Borderlands-Community-Mod-Manager)**.  
Dans l'object explorer, le point le plus pratique est que l'on peut selectioner le texte pour le copier/coller. On peut aussi faire des recherches d'objet si on ne connait pas le nom de ce que l'on veut modifier.  
**[Démonstration en vidéo (2 minutes)](https://youtu.be/uXD2dSlrbVM)**  
Le fichier ou figure tous les materiaux vient d'ici : **[lien](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Dave/Resources)** ("WEAPON MATERIALS")

### Conclusion
**[Application du skin de l'Interfacer sur le Butcher (3.5 minutes)](https://youtu.be/bRBYrEMs_q0)**  
Le fichier ou figure tous les materiaux vient d'ici : **[lien](https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Dave/Resources)** ("WEAPON MATERIALS")
