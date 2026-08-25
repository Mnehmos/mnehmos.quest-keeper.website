# Quest Keeper AI

Quest Keeper AI is a browser-first tabletop adventure: you describe what your character does, a conversational Dungeon Master responds, and the RPG engine keeps the campaign’s important state persistent.

![Status](https://img.shields.io/badge/status-alpha-yellow)
![License](https://img.shields.io/badge/license-Apache%202.0-blue)

## Play now

Enter the [Quest Keeper AI player table](https://play.questkeeperai.com/), create a campaign, build a character, and start playing. The free tier gets you to the table; the optional Player Pass provides more room for a persistent campaign.

The player surface keeps the campaign log, character sheet, inventory, quests, and rules-source attribution together. Tool disclosures can be expanded when you want to inspect an authoritative state change.

## What the engine does

The DM gives committed state a voice; the engine owns the state. The RPG MCP backend currently provides the rules and persistence for:

- D&D character creation, abilities, skills, equipment, and inventory
- NPCs, relationships, memories, and agent-backed NPC hooks
- Checks, combat, damage, healing, rests, and spellcasting
- Quests, objectives, journals, and campaign progression
- Source-aware rules and campaign attribution
- Persistent records that survive a browser refresh and a returning session

Maps, procedural world generation, and domain-scale strategy are later roadmap work, not launch promises.

## Developer path

The open [RPG MCP backend](https://github.com/Mnehmos/mnehmos.rpg.mcp) is the extension point for developers who want to inspect or build on the rules and tool surface. It is a service backend, not a player-facing desktop application.

## Example play

```text
You: I leave the dockside and follow the bells toward the displaced temple.

DM: The bells lead you through salt fog to a drowned cloister. The engine
    records the new place, then the DM describes what waits at its door.

You: I ask the archivist what the black tide is hiding.

DM: The conversation, any check, and any discovered clue become part of the
    campaign record before the answer is narrated.
```

## Documentation

- [Player guide](https://questkeeperai.com/quickstart)
- [API reference](https://questkeeperai.com/api-reference)
- [System analysis](https://questkeeperai.com/analysis)
- [Roadmap](https://questkeeperai.com/roadmap)

## License

Apache License 2.0 — see [LICENSE](LICENSE) for details.

Made with ⚔️ by a solo developer for adventurers.
