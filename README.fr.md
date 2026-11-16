# Gakkel — Mission Console

> English version: [`README.md`](README.md)

Poste opérateur web de [Gakkel](https://github.com/gakkel-labs/swarm-simulator), le simulateur d'essaims de drones sous-marins.

L'opérateur y prépare une mission sur une carte marine S-57 (zone, type de mission, type de recherche, météo GO / NO-GO), reçoit les flottes recommandées par le serveur, les modifie et relance une simulation, puis suit la mission en cours (état, avancement, drones, alertes, commandes).

Le calcul et les simulations restent dans le serveur Java ([swarm-simulator](https://github.com/gakkel-labs/swarm-simulator)). Unity reste l'affichage 3D.

**État : en préparation.** Le travail démarre à l'étape 4 de la roadmap (avril 2027) : voir les [jalons](../../milestones).

## Choix techniques

Le framework du front web (Angular ou React) n'est pas encore choisi : ce sera la première tâche de l'étape 4, notée dans un ADR. Déjà prévu : une carte vectorielle, la connexion OIDC avec Keycloak, et des échanges avec le serveur en REST et WebSocket.

## Licence

[PolyForm Noncommercial 1.0.0](LICENSE) — Copyright (c) 2026 Bourse Alexandre. Usage commercial interdit.
