# DM3 traduction française
> [DDemocracy 3](https://store.steampowered.com/app/245470/Democracy_3/)
*Veillez à bien mettre votre jeu en version anglaise et ensuite aller dans options pour changer la langue et la mettre en français.*  
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
> Electioneering : 21 -> 124
+ 

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
