# Quiz d'entraînement Certiphyto DENSA

Ce dépôt contient un quiz interactif d'entraînement au **Certiphyto (version DENSA)**.  
Il permet de s’exercer à partir d’un pool de questions aléatoires et d’obtenir un score en fin de test.

---

## Fonctionnement

- questions disponibles dans le fichier ( en cours d’enrichissement) `questions.json`
- 30 questions sont tirées **aléatoirement** à chaque session
- Le quiz est **réussi à partir de 15 bonnes réponses**
- Les questions peuvent avoir **plusieurs bonnes réponses**
- Un **retour immédiat** est affiché après chaque validation

---

## Utilisation

Le quiz est accessible en ligne via GitHub Pages :  
[https://JulienCA02.github.io/Quizz-certiphyto-DENSA/](https://JulienCA02.github.io/Quizz-certiphyto-DENSA/)

Pour l’utiliser localement :
1. Télécharger les fichiers `index.html` et `questions.json`
2. Les placer dans le même dossier
3. Ouvrir `index.html` dans un navigateur web

---

## Structure du fichier `questions.json`

Chaque question a la forme suivante :

```json
{
  "q": "Texte de la question",
  "options": ["Réponse 1", "Réponse 2", "Réponse 3"],
  "answers": [0, 2]
}
