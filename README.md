# DM3 traduction française du DLC "Electioneering"
> [Democracy 3](https://store.steampowered.com/app/245470/Democracy_3/)  

**Veillez à bien mettre votre jeu en version anglaise** et ensuite aller dans **options** pour changer la langue et la mettre en **français**.  
Si au démarage du jeu vous choisissez le français vous aurez une version cassée où le DLC "Electioneering" affichera des noms de variables.

## Légende : 
- @( : Ouverture de plusieurs traduction possibles
- ) : fermeture des possibilité
- / : veut dire ça "ou" ça
- @(AAA (b/c)) : plusieurs possibilités rattaché à un même mot
- @(/AAA) : ajout n'existant pas dans la VO

## English version -> option fr 
> Steam\steamapps\common\Democracy 3\translations\Français\data

/strings.ini
> Electioneering : *21 -> 124*  
> Sujet à interprétation sans contexte :  
+ ligne : 46 - 54 : votre parti/du parti
+ ligne : 57 - 76 : manifeste/programme/promesses électorale/engagements électoraux
+ ligne : 108 - 123 : image/perception + ligne 91+90 -> ancienne ligne 23 déplacée)
+ ligne : 113 - 124 : @(une campagne/un @(show/spectacle)) médiatique => Campagne médiatique
> Améliorations de la traduction du jeu  
+ 127 - 128
+ 193
+ 237
+ 450
+ 474 - 477
  

/tutorial.csv
+ 59 -> 67

------------------

## Forgot FR version (if choose in Steam or in first launch)
Ici ce sont toutes les parties manquantes si vous choisissez la version FR de Steam.
> Steam\steamapps\common\Democracy 3\data

Special char like é è € are buged if you edit a file because he use ASCI not UTF transcription.

/dlc.txt
+ line : 3

/simconfig.txt
+ 92 -> 126

/strings.ini
+ 2 -> 106
+ 552 -> 555

/tutorial.csv
+ 59 -> 67

/missions/australia/australia.txt
+ [options] missing
+ 24 -> 26

/missions/*/*.txt
+ [options] missing
- france
- germany 

/simulation/attacks/*Assassination.txt
+ missing : [prereqs] -> *Plot
