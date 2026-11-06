etape 1 : Création du projet et Version V1 (Sur votre ordinateur)
Objectif : Créer le programme de base sur le PC et activer le suivi Git.

Les commandes dans Git Bash de cette etape et le role de chaque commande :

pwd : Permet de vérifier dans quel dossier du PC on se trouve actuellement.
git config : Indique à Git qui vous êtes (votre nom et votre e-mail) pour signer vos futurs enregistrements.
git init : Transforme le dossier de votre ordinateur en un dossier surveillé par Git (il crée l'historique secret).
git status : Affiche l'état actuel du dossier (les fichiers modifiés ou non suivis)
git add main.py : Prépare le fichier main.py pour qu'il soit pris en compte 
git commit -m "..." : Enregistre officiellement la photo (l'instantané) de cette version V1 sur votre ordinateur avec un message 
git log : Affiche la liste de tous les enregistrements (commits) 

Étape 2 : Évolution vers la Version V2 (Ajout du prénom sur le PC)
Objectif : Modifier le code pour demander le prénom, puis valider cette modification en local. 
Le rôle de chaque commande et le role de chaque commande :

git status : Permet de voir que main.py a été modifié 
git add main.py : Prépare la modification du prénom pour l'enregistrement.
git commit -m "V2 - ..." : Crée la deuxième version (V2) de votre code sur votre ordinateur

Étape 3 : Le Premier Envoi sur GitHub (Le git push)
Objectif : Publier le projet (V1 et V2) sur internet pour la toute première fois 
Les commandes dans Git Bash et le role de chaque commande :

git branch -M main : Renomme la branche principale de travail en main
git remote add origin ... : Connecte votre dossier sur votre ordinateur au dossier vide créé en ligne sur GitHub 
git remote -v : Vérifie que le lien vers GitHub est bien configuré
git push -u origin main : Envoie tout votre travail local (V1 et V2) sur le site GitHub  

Étape 4 : La Version V3 (Simulation d'une modif sur GitHub + git pull)
Objectif : Simuler qu'un collègue (ou vous-même sur le site internet) a modifié le code en ligne pour ajouter la matière, puis rapatrier cette modification sur le PC  

Action sur le site web : Modifier le fichier main.py directement sur GitHub et cliquer sur Commit changes avec le message V3 - ajout de la matiere.   

Les commandes dans Git Bash et le role de chaque commande  :
git status : Indique si votre PC est à jour ou en retard par rapport à GitHub
git pull origin main : Récupère (tire) depuis internet les modifications faites sur GitHub pour les fusionner dans votre ordinateur   
git log : Permet de vérifier que le commit de la V3 est bien apparu dans votre historique.


Étape 5 : La Version V4 (Ajout de la durée et nouveau git push)
Objectif : Rajouter la durée des révisions en local sur le PC, puis renvoyer le tout sur GitHub.   
Les commandes dans Git Bash et le role de chaque commande : :
git add main.py et git commit -m "V4 - ..." : Enregistrent la version V4   
git push : Envoie cette dernière version V4 sur GitHub comme le lien -u a été enregistré à l'étape 3  
git log : Affiche l'historique complet et final contenant les 4 versions (V1, V2, V3, V4).   
