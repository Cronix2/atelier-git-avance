# Atelier Git avancé

Projet réalisé dans le cadre de l'atelier Git avancé et collaboratif.

## Stratégie Git

Nous utilisons une stratégie trunk-based.

La branche principale est :

- `main`

Les développements sont réalisés sur des branches courtes.

Convention de nommage :

- `feat/nom-feature`
- `fix/nom-correctif`
- `chore/nom-tache`
- `docs/nom-documentation`

## Règle de merge

Aucun développement ne doit être réalisé directement sur `main`.

Chaque modification doit :

1. être développée sur une branche dédiée ;
2. être poussée sur GitHub ;
3. faire l'objet d'une Pull Request ;
4. être revue avant son intégration dans `main`.

L'objectif est de conserver un historique propre et lisible.
