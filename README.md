# **Présentation du projet : Jeu de devinettes de YouTubers avec IA**

## **1. Objectif d’automatisation**  
Ce projet consiste en un jeu interactif où l'intelligence artificielle (IA) essaie de deviner un YouTuber auquel l'utilisateur pense, en posant une série de questions. Le système utilise un arbre de décision, une structure de données qui prend des décisions en fonction des réponses (oui ou non) de l'utilisateur. Chaque réponse conduit à une nouvelle question, jusqu'à ce que l'IA devine correctement le YouTuber.
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
