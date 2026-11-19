# CATASTERRE — Product Backlog v1

> Export du 19/11/2026, lu dans le projet GitHub : <https://github.com/orgs/manooweb-org/projects/2>.
> SP = story points (effort relatif, tâche de référence à 1 SP). Capacité de départ : 15 SP par sprint.

## #1 Epic 1 — Expérience utilisateur

### #4 US 1 — Style CSS · Haute · 3 SP

Sprint 1 — Livrer les corrections dans une première version conteneurisée

| # | Tâche | Responsable | SP | Statut |
| ---: | --- | --- | ---: | --- |
| 5 | Auditer visuellement les pages | Jorge | 1 | Todo |
| 6 | Corriger le chargement des polices et leurs polices de secours | Dimitry | 1 | Todo |
| 7 | Harmoniser les feuilles de style des thèmes clair et sombre | Dimitry | 1 | Todo |

### #8 US 2 — Messages d'erreur · Haute · 5 SP

Sprint 1 — Livrer les corrections dans une première version conteneurisée

| # | Tâche | Responsable | SP | Statut |
| ---: | --- | --- | ---: | --- |
| 9 | Rédiger la charte des messages et la maquette | Jorge | 1 | Todo |
| 10 | Uniformiser le format d'erreur de l'API (code, message) | Lead dev | 2 | Todo |
| 11 | Intercepter les erreurs HTTP côté Angular | Dimitry | 1 | Todo |
| 12 | Créer le composant d'affichage des messages | Dimitry | 1 | Todo |

### #13 US 3 — Accessibilité · Haute · 8 SP

Sprint 2 — Livrer les corrections d'accessibilité, chacune vérifiée automatiquement

| # | Tâche | Responsable | SP | Statut |
| ---: | --- | --- | ---: | --- |
| 14 | Auditer le parcours principal selon le RGAA (référentiel français) | Jorge | 2 | Todo |
| 15 | Corriger les formulaires et les libellés | Dimitry | 2 | Todo |
| 16 | Corriger la navigation au clavier et l'ordre du focus | Dimitry | 2 | Todo |
| 17 | Corriger les contrastes et les textes alternatifs | Dimitry | 1 | Todo |
| 18 | Tester le parcours avec un lecteur d'écran | Jorge | 1 | Todo |

### #30 US 12 — Observabilité de la production · Haute · 5 SP

Sprint 3 — Préparer, mesures à l'appui, un changement d'architecture sans risque pour la production

| # | Tâche | Responsable | SP | Statut |
| ---: | --- | --- | ---: | --- |
| 31 | Mettre en place la collecte des métriques et un tableau de bord | Rachida | 2 | Todo |
| 32 | Instrumenter le back (durée des requêtes, appels à la base) | Lead dev | 1 | Todo |
| 33 | Mesurer les temps d'affichage côté navigateur | Dimitry | 1 | Todo |
| 34 | Rédiger le rapport des goulots, scénarios de reproduction compris | Lead dev | 1 | Todo |

### #46 US 10 — Compatibilité navigateurs · Moyenne · 3 SP

Sprint 4 — Stabiliser l'application en isolant son goulot d'étranglement (en parallèle ; première reportée si le sprint déborde)

| # | Tâche | Responsable | SP | Statut |
| ---: | --- | --- | ---: | --- |
| 47 | Établir la liste des navigateurs supportés avec le support | Jorge | 1 | Todo |
| 48 | Corriger les incompatibilités et les cibles de compilation | Dimitry | 1 | Todo |
| 49 | Faire la recette croisée | Jorge | 1 | Todo |

## #2 Epic 2 — Disponibilité et architecture

### #19 US 5 — Conteneuriser l'application · Haute · 5 SP

Sprint 1 — Livrer les corrections dans une première version conteneurisée

| # | Tâche | Responsable | SP | Statut |
| ---: | --- | --- | ---: | --- |
| 20 | Construire l'image du back avec un contrôle de santé | Rachida | 2 | Todo |
| 21 | Construire l'image du front | Rachida | 1 | Todo |
| 22 | Sortir la configuration et les secrets du code | Rachida | 1 | Todo |
| 23 | Mettre en production avec un retour arrière prévu | Rachida | 1 | Todo |

### #40 US 6 — Extraire un premier service · Moyenne · 8 SP

Sprint 4 — Stabiliser l'application en isolant son goulot d'étranglement

| # | Tâche | Responsable | SP | Statut |
| ---: | --- | --- | ---: | --- |
| 41 | Cartographier les responsabilités autour du goulot | Lead dev | 2 | Todo |
| 42 | Extraire le service et définir son interface | Lead dev | 3 | Todo |
| 43 | Conteneuriser et déployer le service | Rachida | 1 | Todo |
| 44 | Adapter la CI au nouveau découpage | Rachida | 1 | Todo |
| 45 | Valider en recette, mesures comparées à celles de l'US 12 | Lead dev | 1 | Todo |

## #3 Epic 3 — Fiabilité du développement

### #24 US 7 — Intégration continue · Haute · 5 SP

Sprint 2 — Livrer les corrections d'accessibilité, chacune vérifiée automatiquement

| # | Tâche | Responsable | SP | Statut |
| ---: | --- | --- | ---: | --- |
| 25 | Compiler et tester le front dans GitHub Actions | Rachida | 1 | Todo |
| 26 | Compiler et tester le back dans GitHub Actions | Rachida | 1 | Todo |
| 27 | Ajouter l'analyse du code | Rachida | 1 | Todo |
| 28 | Construire l'image Docker dans la CI | Rachida | 1 | Todo |
| 29 | Protéger la branche principale | Lead dev | 1 | Todo |

### #35 US 8 — Environnement de test · Moyenne · 8 SP

Sprint 3 — Préparer, mesures à l'appui, un changement d'architecture sans risque pour la production

| # | Tâche | Responsable | SP | Statut |
| ---: | --- | --- | ---: | --- |
| 36 | Monter l'environnement de recette en conteneurs | Rachida | 3 | Todo |
| 37 | Préparer un jeu de données de test anonymisé | Rachida | 2 | Todo |
| 38 | Déployer automatiquement depuis la CI | Rachida | 2 | Todo |
| 39 | Écrire la procédure de recette | Jorge | 1 | Todo |

## Hors périmètre pour l'instant (sans sprint)

| # | User story | Priorité |
| ---: | --- | --- |
| 50 | US 4 — Créer un nouveau thème | Basse |
| 51 | US 9 — Améliorer le calcul du risque d'inondation | Luxueuse |
| 52 | US 11 — Améliorer l'exportation des données | Luxueuse |

## Sprints

| Sprint | Objectif | US | SP |
| --- | --- | --- | ---: |
| 1 | Livrer les corrections dans une première version conteneurisée | 1, 2, 5 | 13 |
| 2 | Livrer les corrections d'accessibilité, chacune vérifiée automatiquement | 3, 7 | 13 |
| 3 | Préparer, mesures à l'appui, un changement d'architecture sans risque pour la production | 12, 8 | 13 |
| 4 | Stabiliser l'application en isolant son goulot d'étranglement | 6, 10 | 11 |
| **Total** | | | **50** |

