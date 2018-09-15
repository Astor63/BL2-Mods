Salut Psychopatate

Je commence par les bonnes nouvelles:
### Skin Moxxi "Classic" (modèle Lascaux)
La même teinte de rouge/orange, l'alternance de doré et du même lilas/vieux rose pour les parties métalliques... génial!

![Moxxi Signature "Classic" Collection](https://i.imgur.com/yR8Zjdu.png)
C'est pile-poil ce que je voulais :wink: Encore merci

Pour simplifier mes explications dans ce qui va suivre, je vais nommer la skin que tu as réalisé "Moxxi Classic" (simplement parce qu'elle rentre dans la gamme HeartBreaker/Creamer), et ma skin bordeaux et acier la "Moxxi Cartier" (parce que... ben... bordeaux et acier... et puis plus classe aussi) 
 
### Skin Moxxi "Classic" (modèle Commerce)

Tu n'auras probablement pas remarqué mon update dans mon précédent Readme, mais j'ai décidé de réaliser la Finesse sur base de la Commerce (plutôt que la Lascaux)

Pour installer ta skin sur la Commerce,  j'ai remplacé: 
 ```
 set Common_GunMaterials.Materials.SMG.Mati_DahlUniqueSMG_Lascaux
```
au profit de:
 ```
set Common_GunMaterials.Materials.SMG.Mati_Hyperion_UniqueSMG_Commerce
```

![Moxxi Classic - Lascaux vs Commerce](https://i.imgur.com/Bfm22LM.png)
...et là, le vieux rose des parties métalliques ont bien été transposées, mais pas de rouge/orange de la "coque"... pourquoi?

On dirait qu'il y a un "reflet" métal propres aux skin Hypérion qui se trouve "au-dessus" du rouge/orange, et il faudrait de diminuer ou le mettre sur "0"... mais je suis incapable de déterminer quel est ce paramètre.

Tu as une idée ? 

### Skin Moxxi "Cartier" (modèle Commerce)

Même procédure d'installation que pour la Moxxi Classic

![Moxxi Cartier - Lascaux vs Commerce](https://i.imgur.com/y66VqHp.png)
... et là, c'est le contraire que pour la Moxxi Classic... le rouge s'applique bien, mais les parties métalliques qui étaient brunes deviennent chromées... pourquoi?

Cherchant à comprendre, j'ai repris mon guide, et j'en ai déduis que
![Imgur](https://i.imgur.com/rtAtIwj.png)
  - Acolor modifie la coque de l'arme (en vert fluo)
  - Bcolor modifie les parties métalliques (en couleur fushia)
  - Ccolor modifie le reste des parties métalliques (en bleu)
  
Fort de cette constatation, j'ai réalisé une version v2 de ma skin Moxxi Cartier en recopiant les codes:
- p_BColorHilight - p_BColorMidtone - p_BColorShadow
- p_CColorHilight - p_CColorMidtone - p_CColorShadow

d'une skin Yellow Jacket Hyperion
![Imgur](https://i.imgur.com/HxnUEgf.png)
... mais même après cela, il n'y a toujours aucune modification de couleur "Bcolor" ni "Ccolor"... qui restent chromées pour la Commerce et brunes pour la Lascaux... alors qu'elles devraient devenir similaire à celles de la skin (jaune) Yellow Jacket Hyperion... et cela me laisse pour le moins perplexe.   :unamused:

Qu'est-ce qui empêche l'application de cette modification?

### Questions bonus:

1. J'ai remarqué que tu avais utilisé 
```
Parent Common_GunMaterials.MasterMaterials.Bandit.MasterMati_BanditUncommon
```
Quel en est l'avantage?

2. Dans to ReadMe, tu écris "Recreer/copier le skin d'une arme deja existante est extremement simple, il suffit de dump le materiel de l'arme a copier"
Bonne nouvelle, mais comment fait-on pour "dump le materiel de l'arme a copier" ?
... et ou? dans BLCMM ? dans Gibbed ???


