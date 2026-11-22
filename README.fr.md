# Gakkel — Mission Console

> English version: [`README.md`](README.md)

Le poste de contrôle web de [Gakkel](https://github.com/gakkel-labs/swarm-simulator), un système de missions de drones sous-marins.

L'opérateur y prépare une mission sur une carte marine S-57 (zone de recherche, type de mission, schéma de recherche, météo GO / NO-GO), reçoit les configurations de flotte proposées par le serveur, les modifie et relance une simulation, puis suit la mission en cours (état, avancement, drones, alertes, commandes).

La simulation est une aide, pas une obligation : l'opérateur peut aussi créer une mission seul, de bout en bout, en choisissant lui-même la configuration de flotte.

Plus tard, l'opérateur pourra aussi créer une **campagne** : une suite de plusieurs missions, préparées ensemble. Enregistrer une mission et ouvrir une mission enregistrée viennent d'abord ([#13](https://github.com/gakkel-labs/mission-console/issues/13)). Voir le [glossaire](https://github.com/gakkel-labs/swarm-simulator/blob/main/docs/produit/glossaire.fr.md).

Le calcul et les simulations restent dans le serveur Java ([swarm-simulator](https://github.com/gakkel-labs/swarm-simulator)). Unity reste l'affichage 3D.

**État : en préparation.** Le travail démarre à l'étape 4 de la roadmap (avril 2027) : voir les [jalons](../../milestones).

## Choix techniques

Le framework du front web n'est pas encore choisi : ce sera la première tâche de l'étape 4, notée dans un ADR. Déjà prévu : une carte vectorielle, la connexion OIDC avec Keycloak, et des échanges avec le serveur en REST et WebSocket.

## Licence

[PolyForm Noncommercial 1.0.0](LICENSE) — Copyright (c) 2026 Bourse Alexandre. Usage commercial interdit.
