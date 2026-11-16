# Gakkel — Mission Console

> Version française : [`README.fr.md`](README.fr.md)

Web operator console for [Gakkel](https://github.com/gakkel-labs/swarm-simulator), the underwater drone swarm simulator.

The operator prepares a mission on an S-57 nautical chart (area, mission type, search pattern, GO / NO-GO weather check), receives the fleets recommended by the server, edits them and reruns a simulation, then follows the running mission (state, progress, drones, alerts, commands).

Computation and simulations stay in the Java server ([swarm-simulator](https://github.com/gakkel-labs/swarm-simulator)). Unity stays the 3D view.

**Status: in preparation.** Work starts at step 4 of the roadmap (April 2027): see the [milestones](../../milestones).

## Technical choices

The web front-end framework (Angular or React) is not chosen yet: it is the first task of step 4, recorded in an ADR. Already planned: a vector map, OIDC login with Keycloak, and REST and WebSocket exchanges with the server.

## License

[PolyForm Noncommercial 1.0.0](LICENSE) — Copyright (c) 2026 Bourse Alexandre. Commercial use is not allowed.
