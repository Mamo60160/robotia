Schéma logique

+--------------------------------------------------------------+
|                        Akinator System                       |
|  +-----------------+    +----------------------------+       |
|  |   Interface    |<-->|      Algorithme de          |       |
|  |   Utilisateur  |    |     Prédiction/Analyse      |       |
|  | (Réponses aux  |    |     des réponses            |       |
|  |   questions)   |    |                             |       |
|  +-----------------+    +----------------------------+       |
|           |                        |                         |
|           |                        v                         |
|           |         +----------------------------+           |
|           |         |     Base de données        |           |
|           |         |   - Personnages            |           |
|           |         |- Profils et caractéristiques|          |
|           |         |   - Questions passées      |           |
|           |         +----------------------------+           |
|           |                        |                         |
|           |                        v                         |
|           |         +----------------------------+           |
|           |         |   Système de mise à jour   |           |
|           |         |   - Mises à jour des       |           |
|           |         |     nouveaux personnages   |           |
|           |         |  - Adaptation des algorithmes|         |
|           |         +----------------------------+           |
|           |                        |                         |
|           |                        v                         |
|           |         +----------------------------+           |
|           |         |   Interface externe (API)  |           |
|           |         |   - Connexion avec les     |           |
|           |         |     bases de données       |           |
|           |         |     externes, mises à jour |           |
|           |         +----------------------------+           |
|           |                        |                         |
|           |                        v                         |
|           |         +----------------------------+           |
|           |         |   Moteur de prédiction     |           |
|           |         |  - Prédiction du personnage|           |
|           |         |    en fonction des réponses|           |
|           |              - Affichage des résultats|          |
|           |         +----------------------------+           |
+--------------------------------------------------------------+


Schéma physique
+------------------------------------------+
|               Serveur Principal          |
|  +-------------------------+             |
|  |   Serveur d'Application  |            |
|  |  (Moteur de Prédiction,  |            |
|  |   Algorithmes, API)      |            |
|  +-------------------------+             |
|               |                          |
|               v                          |
|  +-------------------------------+       |
|  | Serveur de Base de Données    |       |
|  | (MySQL, NoSQL, etc.)          |       |
|  | - Stockage des personnages,   |       |       
|  | questions et profils          |       |
|  +-------------------------------+       |
|               |                          |
|               v                          |
|  +-------------------------+             |
|  |   Serveur de Mise à Jour  |           |
|  |   (Mises à jour externes, |           |
|  |     ajout de nouveaux     |           |
|  |     personnages)          |           |
|  +-------------------------+             |
+------------------------------------------+
