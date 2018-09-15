Salut Psychopatate

Je commence par les bonnes nouvelles:
### Skin Moxxi "Classic" (mod�le Lascaux)
La m�me teinte de rouge/orange, l'alternance de dor� et du m�me lilas/vieux rose pour les parties m�talliques... g�nial!

![Moxxi Signature "Classic" Collection](https://i.imgur.com/yR8Zjdu.png)
C'est pile-poil ce que je voulais :wink: Encore merci

Pour simplifier mes explications dans ce qui va suivre, je vais nommer la skin que tu as r�alis� "Moxxi Classic" (simplement parce qu'elle rentre dans la gamme HeartBreaker/Creamer), et ma skin bordeaux et acier la "Moxxi Cartier" (parce que... ben... bordeaux et acier... et puis plus classe aussi) 
 
### Skin Moxxi "Classic" (mod�le Commerce)

Tu n'auras probablement pas remarqu� mon update dans mon pr�c�dent Readme, mais j'ai d�cid� de r�aliser la Finesse sur base de la Commerce (plut�t que la Lascaux)

Pour installer ta skin sur la Commerce,  j'ai remplac�: 
 ```
 set Common_GunMaterials.Materials.SMG.Mati_DahlUniqueSMG_Lascaux
```
au profit de:
 ```
set Common_GunMaterials.Materials.SMG.Mati_Hyperion_UniqueSMG_Commerce
```

![Moxxi Classic - Lascaux vs Commerce](https://i.imgur.com/Bfm22LM.png)
...et l�, le vieux rose des parties m�talliques ont bien �t� transpos�es, mais pas de rouge/orange de la "coque"... pourquoi?

On dirait qu'il y a un "reflet" m�tal propres aux skin Hyp�rion qui se trouve "au-dessus" du rouge/orange, et il faudrait de diminuer ou le mettre sur "0"... mais je suis incapable de d�terminer quel est ce param�tre.

Tu as une id�e ? 

### Skin Moxxi "Cartier" (mod�le Commerce)

M�me proc�dure d'installation que pour la Moxxi Classic

![Moxxi Cartier - Lascaux vs Commerce](https://i.imgur.com/y66VqHp.png)
... et l�, c'est le contraire que pour la Moxxi Classic... le rouge s'applique bien, mais les parties m�talliques qui �taient brunes deviennent chrom�es... pourquoi?

Cherchant � comprendre, j'ai repris mon guide, et j'en ai d�duis que
![Imgur](https://i.imgur.com/rtAtIwj.png)
  - Acolor modifie la coque de l'arme (en vert fluo)
  - Bcolor modifie les parties m�talliques (en couleur fushia)
  - Ccolor modifie le reste des parties m�talliques (en bleu)
  
Fort de cette constatation, j'ai r�alis� une version v2 de ma skin Moxxi Cartier en recopiant les codes:
- p_BColorHilight - p_BColorMidtone - p_BColorShadow
- p_CColorHilight - p_CColorMidtone - p_CColorShadow

d'une skin Yellow Jacket Hyperion
![Imgur](https://i.imgur.com/HxnUEgf.png)
... mais m�me apr�s cela, il n'y a toujours aucune modification de couleur "Bcolor" ni "Ccolor"... qui restent chrom�es pour la Commerce et brunes pour la Lascaux... alors qu'elles devraient devenir similaire � celles de la skin (jaune) Yellow Jacket Hyperion... et cela me laisse pour le moins perplexe.   :unamused:

Qu'est-ce qui emp�che l'application de cette modification?

### Questions bonus:

1. J'ai remarqu� que tu avais utilis� 
```
Parent Common_GunMaterials.MasterMaterials.Bandit.MasterMati_BanditUncommon
```
Quel en est l'avantage?

2. Dans to ReadMe, tu �cris "Recreer/copier le skin d'une arme deja existante est extremement simple, il suffit de dump le materiel de l'arme a copier"
Bonne nouvelle, mais comment fait-on pour "dump le materiel de l'arme a copier" ?
... et ou? dans BLCMM ? dans Gibbed ???


