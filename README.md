# [Echo-part] - Les partitions de musique
Ici sont regroupées toutes les partitions scannées, réécrites et complétées.

## Outils
Voici la liste d'outils utilisés pour ce repository
 - L'application [MuseScore 2.0](https://musescore.org/en/download)
 - Le gestionnaire de sources [Git](https://git-scm.com/download)
 - L'interface graphique pour Git, [GitExtensions](https://github.com/gitextensions/gitextensions/releases/tag/v2.49)

## Organisation
L'organisation des répertoires est assez simple et correspond au titre du morceau.
Ensuite, le contenu peut être parmi les éléments suivants:
 - Un scan PDF correspondant à une version antérieur de la partition, dans ce cas, il faut nommer le fichier ainsi `OLD_nom-du-moreceau_instrument.pdf`
 - Un fichier MSCX correspondant au fichier MuseScore du conducteur, de préférence un fichier non compressé, nommé `nom-du-morceau.mscx`
 - Un fichier MSCX/MSCZ pour un fichier MuseScore pour une partie (spécifique à un instrument), nommé `nom-du-morceau_instrument.mscx`
 - Un/plusieurs fichiers PDF résultat de la production (pour impression), nommé `nom-du-morceau_instrument.pdf` ou `nom-du-morceau.pdf` (si conducteur)
 - Un/plusieurs fichiers MP3 ou MID si génération de la totalité ou un partie de la partition dans un format audio
 
## Format de documents
En fonction de l'utilisation, les documents PDF peuvent être générés dans différents formats.
 - Format A4 portrait, pour utilisation en tant que conducteur ou dans un classeur/trieur
   - Dimensions : 21 x 29.7 (L x H)
   - Marge : 5mm ou 10mm
 - Format MB2F (Marching Band Flip Folder), pour utilisation dans les porte partitions à fixer sur une lyre
   - Dimensions : 171 x 133 (L x H)
   - Marge : 5mm
 - Format Kobo, optimisé pour liseuse Kobo (**à compléter/màj au besoin**)
   - Dimensions : 89 x 119 (L x H)
   - Marge : 1mm

