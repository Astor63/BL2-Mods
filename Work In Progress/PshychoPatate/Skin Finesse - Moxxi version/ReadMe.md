
En fait ce que je voudrais réaliser me semble simple, mais même en suivant pas-à-pas les informations du [Dave'S BL2 Skin Modding Guide](https://cdn.rawgit.com/BLCM/BLCMods/bb1933f7/Borderlands%202%20mods/Dave/DAVE%27S%20BL2%20SKIN%20MODDING%20GUIDE.pdf), je m'emmêle irrémédiablement les pinceaux dans les couleurs.

En fait, dans l'exemple de ligne de code suivante, je comprends parfaitement que les paramêtres R/G/B/A correspondent aux valeurs RGB (comme en photographie), et je sais les obtenir sans problème avec l'outil pipette de Photoshop

```(
    (
        ParameterName = "p_EmissiveColor",
        ParameterValue =
        (
            R = 1.200000,
            G = 0.000000,
            B = 0.600000,
            A = 1.000000
        ),
        ExpressionGUID =
        (
            A = 1475816242,
            B = 1139906328,
            C = -187360584,
            D = -1825963319
        )
    )
)
```
Il me semble donc que la base du rouge "Moxxi signature" que je souhaite obtenir devrait logiquement être:
``` 
ParameterValue =
        (
            R = 179.000000,
            G = 33.000000,
            B = 36.000000,
            A = 54.000000
        )
```
Par contre, je reste complètement hermétique aux valeurs ExpressionGUID = A/B/C/D
```
   ExpressionGUID =
        (
            A = 1475816242,
            B = 1139906328,
            C = -187360584,
            D = -1825963319
        )
```

Voici ce que j'aimerai obtenir comme habillage:

#### La couleur rouge "Moxxi Signature"

Simple à définir: dans le style du Heart Breaker / Creamer

![Moxxi Signature Collection - Moxxi's Red](https://i.imgur.com/lOXtQWL.png)
Et voici le mieux que j'arrive à obtenir... une espèce de rouge "fraise écrasée" qui de plus est brillante comme une Gemstone...
![Finesse Moxxi Version - Moxxi's Red](https://i.imgur.com/mpnjl76.png)
c'est pour le moins assez loin du compte...
![Finesse Moxxi Version - Moxxi's Red](https://i.imgur.com/8gtQFHK.png)
... au moins, je peux me consoler en me disant que le logo Moxxi est bien positionné sur la crosse  :smile:

#### Les parties métalliques "Moxxi Signature"

Par rapport, à l'habillage original de la Lascaux, voici ce que j'obtiens

![Finesse Moxxi Version - Metal Part](https://i.imgur.com/9Z6V0yW.png)
Et voici ce que j'aimerai obtenir
![Finesse Moxxi Version - Moxxi's Red](https://i.imgur.com/Ko9vwnP.png)
