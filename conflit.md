# Les conflits, qu'est-ce que c'est ?

## Definition

Quand on travail sur un projet, il arrive que plusieurs personnes travaillent sur le même fichier, dans ce cas là lors de la synchro Git fusionne automatiquement les differentes versions du fichier, on dit qu'il "merge" les fichiers, mais quand deux personnes modifient le même endroit d'un même fichier en même temps un conflit apparait. Le fichier a été PUSH avec des modification pendant que quelqu'un avait Commit des modifications sur le même fichier au même endroit, avant de PUSH, il fait son PUSH pour être a jour, et lors de la fusion (le merge) **BAM** Conflit ! 

## Comment le résoudre ?

Git gère bien les conflit, il rajoute de nouvelles lignes dans le fichier pour delimiter le conflit et montre les differentes versions pour permettre de choisir la version a garder. Il faut ensuit rajouter le fichier au projet avec "git add <filename>"

