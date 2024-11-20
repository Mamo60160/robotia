# **Akinator avec Interaction Vocale**

## **1. Objectif d’automatisation**  
L'objectif principal de ce projet est de créer une version interactive du jeu **Akinator**, qui permet à l'utilisateur de répondre aux questions par la voix et de recevoir des réponses vocales en retour. Ce système combine des algorithmes d'intelligence artificielle pour deviner un personnage en fonction des réponses données à une série de questions, tout en offrant une expérience plus immersive grâce à l'audio.

---

## **2. ODD (Operational Domain Design)**  
Voici le diagramme de conception opérationnelle (ODD) pour le projet **Akinator avec interaction vocale**.  
- Exemple :  
  ![Diagramme ODD](ODD.md)  
  - **Valeur limite 1** : Les réponses vocales doivent être claires et compréhensibles.
  - **Valeur limite 2** : L'algorithme de prédiction doit donner une réponse correcte avec une précision minimale de 90%.

---

## **3. Schéma d'architecture logique et physique**  
### Architecture logique :
Le schéma d'architecture logique décrit l'organisation des différents composants du système, de l'interface utilisateur au moteur de prédiction.
- Architecture logique : ![Schéma logique](ARCHITECTURE_LOGIQUE_PHYSIQUE.md)  

### Architecture physique :
Le schéma d'architecture physique présente les éléments matériels nécessaires au fonctionnement du système (microphone, haut-parleurs, microcontrôleur).
- Architecture physique : ![Schéma physique](ARCHITECTURE_LOGIQUE_PHYSIQUE.md))  

---

## **4. Schéma électronique**  
Voici un schéma des composants électroniques utilisés pour permettre l'interaction vocale avec l'utilisateur.
- Schéma électronique : ![Schéma électronique](SCHEMA_ELECTRONIQUE.md)  

---

## **5. Base de données et fichiers de test**  
Le projet utilise une base de données pour stocker les informations sur les personnages et leurs caractéristiques.  
- **URL de la base de données** : [Base de données Akinator](lien_vers_la_base)  

### Exemple de fichier de test (questions et réponses) :
```json
{
  "question1": "Est-ce un personnage réel ?",
  "réponse1": "Oui",
  "question2": "Est-ce que cette personne est célèbre ?",
  "réponse2": "Oui"
}
