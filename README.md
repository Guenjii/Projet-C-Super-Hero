=========================================
   SUPERHEROS MANAGER - Application en C
=========================================

-----------------------------------------
 DESCRIPTION DU PROJET
-----------------------------------------

SuperHeros Manager est une application en ligne de commande developpee
en langage C. Elle permet de consulter, rechercher, filtrer et comparer
des super-heros a partir d'un fichier de donnees au format JSON
(SuperHeros.json) contenant 16 super-heros.

Les donnees de chaque heros incluent ses statistiques de combat
(intelligence, force, vitesse, durabilite, pouvoir, combat) ainsi que
ses informations d'apparence (genre, race, taille, poids, couleur des
yeux et des cheveux).

Fonctionnalites disponibles :
  - Lister tous les heros (ID + Nom)
  - Rechercher un heros par son ID
  - Rechercher un heros par son nom (insensible a la casse)
  - Filtrer les heros selon une statistique et un seuil
  - Comparer deux heros cote a cote avec verdict final


-----------------------------------------
 PREREQUIS
-----------------------------------------

Aucune installation requise.
L'executable heroes.exe est fourni directement dans le depot.

Le programme necessite uniquement le fichier SuperHeros.json
present dans le meme dossier que l'executable.


-----------------------------------------
 UTILISATION
-----------------------------------------

1. Telecharger les fichiers du depot.

2. Verifier que le dossier contient bien :

    heroes.exe
    SuperHeros.json

3. Ouvrir un terminal dans ce dossier et executer :

    heroes.exe

IMPORTANT : le fichier SuperHeros.json doit se trouver dans le
meme dossier que heroes.exe au moment du lancement.


-----------------------------------------
 OUTILS UTILISES
-----------------------------------------

  Langage      : C (standard C99)
  Compilateur  : GCC (MinGW sur Windows)
  Bibliotheque : cJSON 1.7.18 (parsing JSON)
  Donnees      : SuperHeros.json (16 heros)


-----------------------------------------
 AUTEUR
-----------------------------------------

  BIHINA Florent - TP Programmation en C - 2026

=========================================
