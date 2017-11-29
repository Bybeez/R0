#Le principe du PUSH et du PULL

##Le PUSH

Le PUSH permet de "pousser", d'envoyer, des modifications sur le serveur git (dans notre cas, gitHub).

Les modifications a envoyer doivent d'abord etre commit, et personne de doit avoir fait de PUSH depuis le dernier PULL.
Il vaut donc mieux faire un PULL avant de PUSH.
##Le PULL

Le PULL permet de "tirer", de telecharger, les nouvelles modifications du projet.

  Deux possibilitees : 
   - Aucune modification du projet en local depuis le dernier PULL -> fast-forward
   - Des modifications ont ete *commit* en local, les changements seront automatiquement fusionnes, et en cas de conflit garde les deux possibilitees pour permettre de choisir manuellement
