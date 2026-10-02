# Grilles Projet et Contexte

Application web pour qualifier un projet de changement et choisir la stratégie de conduite du changement adaptée.

## Principe

Deux questionnaires de 15 questions chacun, notées de 1 (facteur de difficulté fort) à 4 (facteur facilitant) :

- **Grille 1, le projet** : facile ou difficile ? Blocs *Ampleur*, *Exigence*, *Conduite*.
- **Grille 2, le contexte** : favorable ou défavorable ? Blocs *Histoire et confiance*, *Capacités*, *Culture et engagement*.

Chaque grille est notée sur 60. Le seuil de bascule est 38 (moyenne de 2,5 par question).

## Les quatre stratégies

|                      | Contexte favorable | Contexte défavorable |
|----------------------|--------------------|----------------------|
| **Projet difficile** | Planification      | Co-construction      |
| **Projet facile**    | Déploiement        | Consultation         |

| Stratégie       | Livrables | Coût (part du coût du projet) |
|-----------------|-----------|-------------------------------|
| Déploiement     | 7         | 3 %                           |
| Planification   | 13        | 6 %                           |
| Consultation    | 19        | 10 %                          |
| Co-construction | 23        | 15 %                          |

Les outils (O1 à O23) sont répartis en **Diagnostic**, **Leviers** et **Pilotage**, et s'additionnent d'une stratégie à l'autre.

## Fonctionnalités

- Matrice projet × contexte avec la position du projet
- Scores par grille et par bloc, points d'attention (réponses notées 1 ou 2)
- Stratégie recommandée : définition, logique, actions, rôles, risque
- Liste des outils à réaliser et coût, calculé en euros à partir du budget du projet
- Synthèse copiable en un clic
- Réponses enregistrées dans le navigateur (localStorage), aucune donnée envoyée à un serveur
- Exemple prérempli : traçabilité par lot dans l'entreprise fictive JNO

## Utilisation

Ouvrir `index.html` dans un navigateur. Aucune installation ni dépendance : un seul fichier HTML, CSS et JavaScript.

## Publier avec GitHub Pages

1. Créer un dépôt sur GitHub et y déposer `index.html`, `README.md` et `.nojekyll`.
2. Dans le dépôt : **Settings → Pages → Build and deployment → Source : Deploy from a branch**, branche `main`, dossier `/ (root)`.
3. L'application est en ligne à l'adresse `https://<votre-compte>.github.io/<nom-du-depot>/`.

## Auteur

David Autissier
