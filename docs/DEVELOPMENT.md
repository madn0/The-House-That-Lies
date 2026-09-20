# Development Notes

## Phase 0 — Foundation

We are starting small on purpose.

The first job is not to build anomalies, monsters, chases, or story systems. The first job is to prove that the development workflow works reliably.

### Responsibilities

- **Roblox Studio:** map, models, props, lighting, sounds, and testing.
- **GitHub:** version-controlled Luau source code.
- **Server code:** authoritative game logic that runs on the Roblox server.
- **Client code:** player-specific behaviour that runs for each player.
- **Shared code:** configuration or modules that both sides may need.

### First test

Sync the Server and Client source folders into suitable Roblox Studio containers, start a play test, and check Output.

Expected messages:

```
[THE HOUSE THAT LIES] Server started.
[THE HOUSE THAT LIES] Client started.
```

Do not add gameplay systems until this test works. That keeps failures easy to understand and gives the project a known-good starting point.

## Coding rule

New Roblox/Luau concepts should be introduced gradually and explained before the project becomes dependent on them. The aim is not merely to make the game work; the codebase should remain understandable to the people building it.
