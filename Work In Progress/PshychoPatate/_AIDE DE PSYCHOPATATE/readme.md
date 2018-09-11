Dans ce dossier tu pourras trouver **Moxxi.txt** qui contient seulement 4 lignes qui fais juste le skin de la version Moxxi:
![image](https://i.imgur.com/ZEsozwb.png)
J'esperes que mes conseils te seront utiles :)

### Général :

- L'EmissiveColor est utilisé uniquement quand l'arme est **non-elementale**. Ca ne change donc pas le rouge/orange des armes incendiaires ou autres elements.
- Je ne crois pas qu'il soit possible de donné une couleure emissive unique a une arme elementale.
- Recreer/copier le skin d'une arme deja existante est extremement simple, il suffit de dump le materiel de l'arme a copier, tout les parametres sont la, **PAR CONTRE**, tout les parametres ne marcherons pas de la meme facons sur une arme de type différente (smg/shotgun)
- Les valeurs A, B, C et D de "ExpressionGUID" qu'il y a dans a peu pres tout les parametres n'ont aucun effets.
- Les couleurs a mettre dans les valeurs R, G et B **ne sont pas des codes sur 256**, je crois que c'est une sorte de multiplicateur, mais meme en pensant comme ca, certainnes choses ne sont pas coherentes. Pour faire simple, plus la valeur est haute plus ca va etre clair/brillant.
- Sur certain parametres (EmissiveColor...) mettre le code RGB a 0 rendra **invisible** et pas noir.

### 1 - Moxxi version :

- Pour la couleur principale, le probleme vient du fait que l'on ne puisse pas utiliser de code RGB pour avoir ce que l'on veut, comme expliqué juste au dessus.
- Le probleme de couleur des parties metaliques a l'air d'etre le **pattern**, j'ai essayer pleins de modifications sur les "ReplacePattern" ou les "ChannelScale" mais impossible de mettre une couleur normale. La couleur du pattern s'imposait sur **tout** le channel sur lequel il est. J'ai donc pas mis de pattern du tout.

### 2 - Lascaux version :

- Meme probleme qu'au dessus, on peut pas utiliser les codes RGB.

### 3 - Conseil/suggestion :

Pour ce qui est d'afficher l'element sur la carte je n'ai jamais essayer mais j'ai peut-etre une piste: Dans les dump de **PartList** et **WeaponPartListCollectionDefinition_176** de la lascaux, on peut trouver la ligne :  
**ElementalPartData=([...],WeightedParts=((Part=WeaponPartDefinition'GD_Weap_SMG.elemental.SMG_Elemental_None',[...])))**  

Pour l'affichage des degats elementaux sur la carte, je ne suis pas sur qu'il soit possible de les afficher sur une arme non-elementale.