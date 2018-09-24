

## BL2-RGB v2
 
En annexe, tu trouveras le fichier Excel BL2-RGB-V2, que j'ai amélioré ce week-end pour qu'il s'adapte au résultat visuel de [encycolorpedia]

Le site permet de visualiser la couleur choisie avec les résultat obtenus avec 25% de saturation et 25% de dé-saturation.

Pour correspondre à ces valeurs visuelles, le calcul s'effectue maintenant sur la base de la valeur précédemment obtenue (et non plus bêtement ajouter 25% -sans effet cumulatif- à la *valeur normale*)

- Valeurs saturées, la valeur 6 correspond à la valeur 5 +25%, la *valeur 7* correspond à la *valeur 6* +25%, etc... 

- Valeurs dé-saturées: La *valeur 4* correspond à la *valeur 5* -25%, la valeur 3 correspond à la *valeur 4* -25%, etc...

![Pourcentage RGB](https://imgur.com/tDlmudd.jpg)

Le résultat obtenu avec la feuille de calcul Excel peut donc être visualisé directement sur le site encycolorpedia

![Pourcentage RGB](https://imgur.com/zmCbHZC.jpg)

**Note:** Je tâtonne encore un peu pour comprendre quel est la meilleur proportion à utiliser pour obtenir la *valeur 5*, et c'est la raison pour laquelle il y a 2 feuilles de calculs.
1. *Proportion 50* : les résultats obtenus conviennent très bien pour des couleurs claires.
2. *Proportion 20* : les résultats obtenus conviennent mieux pour des couleurs sombres.

Exemples:
- si je traite le "jaune explosif" en *proportion 20*, et que je choisis un résultat dans les valeurs 6-10, un effet de "glow" va s'appliquer sur la couleur, en revanche, la couleur sera tip-top en *proportion 50*
- si je traite la couleur "rouge sang" (presque bordeaux) en *proportion 50*, la couleur sera assez lumineuse et semi-transparente, mais sera tip-top (profonde et opaque) en *proportion 20*

J'espère que ce petit outil te sera utile

Astor
*****
