# The House That Lies

A Roblox psychological horror game where the house changes, watches, learns, and eventually hunts the player.

## Current development stage

**Phase 0 — Foundation**

The current goal is deliberately simple: prove that code stored in this repository can be synced into Roblox Studio and run successfully.

## Phase 0 success condition

When the place is started in Roblox Studio, Output should contain:

```
[THE HOUSE THAT LIES] Server started.
[THE HOUSE THAT LIES] Client started.
```

Once both messages appear, the basic code pipeline is working.

## Project structure

```
src/
├── Server/
│   └── GameServer.server.luau
├── Client/
│   └── GameClient.client.luau
└── Shared/
    └── Config.luau
```

The real map is intentionally not part of this phase. Studio remains the home of the physical house, while this repository tracks the game's Luau code.
