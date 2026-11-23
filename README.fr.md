# Gakkel — Mission Console

> English version: [`README.md`](README.md)

Le poste de contrôle web de [Gakkel](https://github.com/gakkel-labs/swarm-simulator), un système de missions de drones sous-marins.

L'opérateur y prépare une mission sur une carte marine S-57 (zone de recherche, type de mission, schéma de recherche, météo GO / NO-GO), reçoit les configurations de flotte proposées par le serveur, les modifie et relance une simulation, puis suit la mission en cours (état, avancement, drones, alertes, commandes).

La simulation est une aide, pas une obligation : l'opérateur peut aussi créer une mission seul, de bout en bout, en choisissant lui-même la configuration de flotte.

Le calcul et les simulations restent dans le serveur Java ([swarm-simulator](https://github.com/gakkel-labs/swarm-simulator)). Unity reste l'affichage 3D.

**État : en préparation.** Le travail démarre à l'étape 3 de la roadmap, juste après l'étape 2 : voir les [jalons](../../milestones).

## Choix techniques

Le framework du front web n'est pas encore choisi : ce sera la première tâche de l'étape 3, notée dans un ADR. Déjà prévu : une carte vectorielle, la connexion OIDC avec Keycloak, et des échanges avec le serveur en REST et WebSocket.

## Licence

[PolyForm Noncommercial 1.0.0](LICENSE) — Copyright (c) 2026 Bourse Alexandre. Usage commercial interdit.
