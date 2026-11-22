# Gakkel — Mission Console

> Version française : [`README.fr.md`](README.fr.md)

The web control station of [Gakkel](https://github.com/gakkel-labs/swarm-simulator), a mission system for underwater drones.

Here the operator prepares a mission on an S-57 nautical chart (search area, mission type, search pattern, GO / NO-GO weather check), receives the fleet configurations proposed by the server, edits them and runs a simulation again, then follows the mission in progress (state, progress, drones, alerts, commands).

The simulation is a help, not a must: the operator can also create a mission alone, from start to end, and choose the fleet configuration themselves.

Computation and simulations stay in the Java server ([swarm-simulator](https://github.com/gakkel-labs/swarm-simulator)). Unity stays the 3D view.

**Status: in preparation.** Work starts at step 4 of the roadmap (April 2027): see the [milestones](../../milestones).

## Technical choices

The web front-end framework is not chosen yet: it is the first task of step 4, recorded in an ADR. Already planned: a vector map, OIDC login with Keycloak, and REST and WebSocket exchanges with the server.

## License

[PolyForm Noncommercial 1.0.0](LICENSE) — Copyright (c) 2026 Bourse Alexandre. Commercial use is not allowed.
