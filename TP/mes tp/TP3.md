Création de plusieurs Branche : git branch "TP3" - git branch "TP3 annex"


Déplacement dans le fichier TP3 : git checkout TP3
Création du fichier TXT - touch fichier.txt
Sauvegarde - git add . et git commit


Déplacement dans le fichier TP3annex : git checkout TP3-annex
Création du fichier TXT - touch fichier.txt
Sauvegarde - git add . et git commit

Déplacement dans le fichier TP3 : git checkout TP3

fusion de ses deux branch a l'aide d'un merge : git merge "TP3 annex"

Une erreur survient quand ont merge car le fichier txt a le meme nom, on retourne sur TP3 pour rename le fichier txt puis on ressaye de merge.

Puis une fois merge, on peut delete le branche TP3 annex

git branch -d TP3-annex
