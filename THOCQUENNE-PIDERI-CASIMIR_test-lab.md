# Test lab

**1.1** : Dans l'invite de commande, "~" est un accès rapide à `$HOME`, la variable d'environnement contenant le dossier utilisateur. Exemple : `$ echo ~` renvoie `/home/raphael`

**1.2** :

* `VV=3` : Crée une variable nommée VV valant 3, et visible uniquement dans le shell actuel
* `export VV` : modifie la portée de la variable. Elle a désormais une portée globale, copiée dans tous les programmes exécutés dans le contexte local.
* `bash` : Lance l'interpréteur de commande "bash".
* `unset VV` : Supprime la variable dans le shell actuel / local.
* `exit` : Quitte le bash actuel.
* `echo $VV` : Renvoie 3 car la variable n'a pas été supprimée dans cet environnement 