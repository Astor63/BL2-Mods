

## Un petit cadeau (si, si...)
 
En annexe, tu trouveras un fichier Excel, c'est un petit outil fait maison qui simplifite la vie, mais surtout pour **ne plus aller chercher les couleurs "à la louche"** pour réaliser une skin :wink:

Pour l'utiliser, rien de plus simple:
1. Tu ouvres mon fichier Excell (ben oui, tout de même!)
2. Tu vas choisir une couleur sur le site [encycolorpedia](https://encycolorpedia.com/)
![Pourcentage RGB](https://imgur.com/mFL5rHR.jpg)

3. Quand tu as trouvé ta couleur, tu verras une mention reprenant les pourcentages de RGB (surligné en bleu sur la photo ci-dessous)
 ![Pourcentage RGB](https://imgur.com/6X0uqFK.jpg)
4. Tu indiques ces 3 pourcentages RGB dans les 3 cellules grisées (en haut de la page)
5. Tu prononces la formule magique... et si tu ne t'en souviens plus, appuies simplement sur Enter.
![Excell](https://imgur.com/k3O320W.jpg)
Et hop! Tous les codes apparaissent comme par enchantement

Voici ce à quoi correspondent les codes obtenus.
- Dans le bloc en gras (#5), ce sont les valeurs "normales" pour une couleur pleine.
**Note:** Descendre ou monter d'une ligne, te donneras la même couleur, mais dans une autre intensité... je vais t'expliquer cela plus bas avec une exemple.
- Les valeurs de 6 à 10 sont saturées par tranches de 25 et peuvent servir pour p_highlight (si tu veux juste un effet de luminosité de la même couleur)
- Les valeurs de 4 à 0 sont dé-saturées par tranches de 25 et peuvent servir pour p_shadow (si tu veux juste un effet d'ombre de la même couleur)
- Les valeurs de -1 à -4 deviennent progressivement transparentes par tranches de 25% et peuvent convenir pour:
  - un effet de p_highlight ou p_shadow très léger (qui ne viendra pas "trop" écraser la couleur "normale" puisque cette valeur est semi-transparent) 
  - le fameux p_EmissiveColor (puisque la couleur élémentale viendra l'écraser par dessus)
### Exemple
Dans le cas de mon Discord Solver, je me suis dit que si on pouvait trouver cette SMG (Lascaux) trainant depuis des lustres dans une grotte, pourquoi devait elle bliquante et reluisante comme un sous neuf, comme si elle venait juste de sortir de chez un armurier?

Partant de cette constatation, j'ai décidée de réaliser une skin de couleur unie, que j'allais salir.

Pour faire simple et rester dans la gamme Dahl, j'ai choisi comme base la couleur de la skin de la Gween's Head, et j'ai sélectionné la couleur avec l'outil Pipette de Photoshop qui m'a donné le code #9a846c

![Gwen's Head](https://imgur.com/TWBhBGJ.jpg)

J'ai collé de code dans Encycolorpedia...

![Pourcentage RGB](https://imgur.com/6X0uqFK.jpg)

... qui m'a gentiment donné les % RGB que j'ai inséré dans ma table Excel

![Excell](https://imgur.com/k3O320W.jpg)
Et j'ai recopié le résultat obtenu en valeur 5 dans BLCMM et j'ai obtenu exactement la même couleur que la Gwen's Head sur ma Discord Solver.

Ensuite, j'ai ajouté:
- La paterne BanditRare pour donner un aspect crasseux à l'arme.
- Le "filtre fumée" ZedVendingMachine_Burned sur P_SimpleReflect (qui est généralement utilisé pour ajouter un effet de lumière de type Glossy) afin de la rendre terne, matte et -surtout- lui faire perdre tous ses reflets.

Et voici le résultat obtenu:
![Excell](https://imgur.com/4XwasLx.jpg)
Ce n'était pas mal, l'effet métal mat et crasseux était obtenu, mais les 2 filtres appliqués successivement avaient assombrit la couleur du Gwen's Head (un peu comme si on la regardait au travers d'une vitre fumée) pour devenir Olive... et cela faisait trop couleur militaire à mon goût.

J'ai repris ma table excell pour choisir une valeur de zone 6 (saturée à 25%) ou 7 (saturée à 50%)...
![Excell](https://imgur.com/k3O320W.jpg)
... qui a immédiatement boosté la luminosité de la couleur de la coque de la SMG pour fait revenir -sous la crasse- à la teinte de la Gwen's Head. 

Et hop! Le tour était joué...
![Excell](https://imgur.com/s9HHHYT.jpg)
Trouver et/ou adapter/corriger une couleur est devenu un jeu d'enfant :wink:
Temps de réalisation: 20 minutes


Amuses-toi bien

**Note:** Dans le cas ou tu utilises un effet de lumière sur P_SimpleReflect, ta couleur de base deviendra forcément plus claire (le contraire de mon exemple ci-dessus) et pour la "rattraper", tu devras choisir une valeur dé-saturée de ta couleur (zone  0 à 4) 
* * * * *
