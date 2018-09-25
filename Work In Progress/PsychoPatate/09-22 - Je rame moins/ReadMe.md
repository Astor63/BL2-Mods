
Avant toute chose, je voudrai te remercier pour tes tutoriaux en video (AIDE 16-09-18)... maintenant c'est -presque!- un jeu d'enfant pour créer une skin.

Bon, je n'y arrive pas encore en moins de 5 minutes comme sur ton exemple Butcher/Interfacer, mais j'arrive à réaliser une skin pas trop moche en 15/30 minutes... 10 minutes pour remplacer les 3 fichiers "parameter"... et  dans le cas de la Bloody Skin, 15/20 minutes pour chipoter à faire des essais avec les 3 paternes "sang" différentes, puis déplacer la paterne "sang" qui me convient le mieux pour avoir un bel effet

Et voilà le travail:
![Discord Solver - Bloody Edition](https://i.imgur.com/jTwGJgh.png)
__Quizz:__ Est-ce que les "parameter" de la skin utilisées sont flagrants, ou faut-il réfléchir un instant pour le découvrir?

Mais je rencontre encore quelques problèmes

### Finesse (Commerce)

J'ai un souci avec la couleur de la coque de l'arme avec les 2 skin Moxxi (Classic & Cartier) lorsque j'essaye de les porter sur la Finesse (créée sur la base de la Commerce)... on dirait qu'il y a une paterne metallique qui est appliquée par-dessus.

Pour installer la skin, j'ai changé le début des 4 lignes de code:
 ```
set Common_GunMaterials.Materials.SMG.Mati_DahlUniqueSMG_Lascaux
 ```
 au profit de:
  ```
 set Common_GunMaterials.Materials.SMG.Mati_Hyperion_UniqueSMG_Commerce
 ```
 Et j'ai laissé la ligne de code "Parent" inchangée puisqu'elle provient de la skin originale du HeartBreaker 
 
 ```
 set Common_GunMaterials.Materials.SMG.Mati_Hyperion_UniqueSMG_Commerce Parent Common_GunMaterials.MasterMaterials.Bandit.MasterMati_BanditUncommon
  ```
Jusque là, il me semblait avoir tout bon... et bien non... car voici ce que j'obtiens:

![Imgur](https://i.imgur.com/FefmhbC.png)

... alors, j'ai refais la skin 2x en partant du HeartBreaker, puis du Creamer... même résultat.

Comme j'avais remarqué en dumpant toutes les armes Moxxi que certaines d'entre elles utilisaient le code

```
set Common_GunMaterials.Materials.SMG.Mati_Hyperion_UniqueSMG_Commerce Parent Material'Common_Materials.Weapons.Master_Gun'

```
Je me suis dit que cela valait la peine de faire un essai en modifiant le paramêtre parent sur 

```
set Common_GunMaterials.Materials.SMG.Mati_Hyperion_UniqueSMG_Commerce Parent Material'Common_Materials.Weapons.Master_Gun'

```
Ben non... toujours le même résultat

![Imgur](https://i.imgur.com/a9FQkMe.png)

Et le pire, c'est que la skin cartier modifiée, donne le résultat contraire

![Imgur](https://i.imgur.com/0fKY789.png)

Alors je me suis mis à examiner attentivement le codage de la skin de la Moxxi Classic et celle de la Commerce, et j'ai remarqué ces -grandes?- différences dans le code:


- Skin Moxxi Classic (2 Lignes de code)
 ```
(ParameterName="p_ReplacePattern",ParameterValue=1.000000,ExpressionGUID=(A=-2084339847,B=1096440125,C=439008937,D=45433490))
(ParameterName="P_SimpleReflect",ParameterValue=Texture2D'Common_GunMaterials.Env.GlossyC',ExpressionGUID=(A=-858148940,B=1327945772,C=148462268,D=1899047224)),
 ```
 
- Skin Commerce (2 lignes de codes)
```
(ParameterName="p_ReplacePattern",ParameterValue=0.000000,ExpressionGUID=(A=-2084339847,B=1096440125,C=439008937,D=45433490))
(ParameterName="P_SimpleReflect",ParameterValue=Texture2D'Common_GunMaterials.Patterns.Pattern_Lightning',ExpressionGUID=(A=-858148940,B=1327945772,C=148462268,D=1899047224))
```
 Et 3 lignes en plus (qui ne sont pas écrasées par le fichier de ta skin Moxxi ni par celui de la HeartBreaker)
```
ScalarParameterValues(4)=(ParameterName="p_UseFullColorDecal",ParameterValue=0.000000,ExpressionGUID=(A=-1064329812,B=1077705328,C=339664807,D=1869745420))
VectorParameterValues(10)=(ParameterName="p_ReflectionChannelScale",ParameterValue=(R=1.000000,G=0.400000,B=0.000000,A=1.000000),ExpressionGUID=(A=1869386622,B=1303200947,C=-1616405849,D=714558284))
VectorParameterValues(12)=(ParameterName="p_DecalColor",ParameterValue=(R=1.730582,G=3.275289,B=6.960011,A=1.000000),ExpressionGUID=(A=1691998600,B=1239094551,C=2074257317,D=1844701893))
```
J'ai passé 4 heures à essayer de trouver ce qui coince, mais sans résultat... à part les 3 lignes en plus dans la skin de la Commerce, mais si le souci provient bien de là, j'ignore la manière d'y remédier!

Tu aurais une idée?

## Update 22/9

Je viens d'installer la skin Bloody de la DIscord Solver sur la Commerce, et, contre toute attente, elle va parfaitement!

![Skin Grunge Lascaux on Commerce](https://imgur.com/zIpAGUV.jpg)

La skin est crasseuse et terne à souhait... bref tout est tip-top... après cette (bonne) surprise, je ne comprends vraiment pas pourquoi les 2 skin Moxxi ne vont pas ???

## Note:

Dans ton aide du 16/9, tu écris: "Tout d'abord, je suis très étonné de voir que tu as fais tout ca sans jamais avoir utilisé de dump."

Ben maintenant que sais comment faire un dump, cela va être nettement plus facile pour tout, aussi bien pour créer une arme que pour faire une skin.

En fait, j'utilise le système vielle école, le bon vieux Notepad+, et je regarde comment d'autres modders on fait pour réaliser une arme afin de comprendre la marche à suivre pour procéder.

Dans le cas de la SMG à balle GyroJet explosive, j'ai constaté qu'il n'y avait pas de SMG à balles explosive (de type Torgue).

Il y a bien eu une tentative par le passé réalisée sur la base d'une SMG Maliwan, la [Dynamite](https://github.com/BLCM/BLCMods/blob/af3b2d17629ab3f7f7a5f7bb68b489c5e13b0498/Borderlands%202%20mods/darkpouetman/Dynamite%20-%20Explosive%20Torgue%20SMG.txt)... mais je ne trouvais pas le résultat très convaincant.

Alors en regardant comment d'autres moddeurs avait procédé, par exemple pour la [Melt](https://github.com/BLCM/BLCMods/blob/master/Borderlands%202%20mods/Aaron0000/Submachine%20Guns/Melt.txt) sur base de la Hellfire ou la [Entendre](https://github.com/BLCM/BLCMods/blob/master/Borderlands%202%20mods/Aaron0000/Submachine%20Guns/Entendre.txt) sur base de la Chulain, il m'a suffit de réfléchir un peu à la manière de procéder, de coucher mes idées sur Notepad, d'ajouter un peu de magie Vaudou lorsque mon code était récalcitrant... et hop, le tour est joué!

En balançant la Discord Solver pour qu'elle ne soit pas "trop" puissante, j'ai eu d'autres idées pour l'améliorer, mais je vais  laisser la version SMG telle qu'elle est actuellement, et je vais créer une version E-Tech (Plasma Caster) qui sera une arme vraiment différente, (les balles perdues n'exploseront plus "bêtement", mais disparaîtront en fumée rose d'impact plasma à la manière d'un pétard mouillé... et puis il y aura une "imperfection" dans l'arme qui produira un effet surprise quand l'arme est utilisée sous certaines conditions... et que j'espère surprenant... mais je n'en dit pas plus pour l'instant... patience, elle sera bientôt finie :wink: