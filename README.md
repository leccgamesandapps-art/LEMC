# LEMC

**LEMC** (LE-MC-HOST Core) is the internal, locked mod that is automatically installed on every server created through the [LE-MC-HOST](https://github.com/leccgamesandapps-art/LE-MC-HOST-SOURCE) website.

## What is LEMC?

- **Locked** — Cannot be removed from the server
- **Linked** — Connected to the same Xbox account that owns the server on LE-MC-HOST
- **Config Sync** — Server Config on the website ↔ LEMC Config Item in-game stay synchronized
- **Ownership** — The server is always owned by the Xbox Gamertag that created it

## How it works

```
Xbox Gamertag (Account)
        │
        ▼
LE-MC-HOST Website  ←────→  Minecraft Server
        │                         │
        └──────── LEMC ───────────┘
                 (locked)
```

1. User signs in with Xbox on LE-MC-HOST
2. User creates a server → LEMC is automatically added and locked
3. Server Config changes on the website update the LEMC Config Item
4. Using the LEMC Config Item in-game opens / reflects the same Server Config

## Official Website

The source of the LE-MC-HOST website is private:

→ **[LE-MC-HOST-SOURCE](https://github.com/leccgamesandapps-art/LE-MC-HOST-SOURCE)** (private)

## Mod List

| Mod | Status | Description |
|-----|--------|-------------|
| **LEMC** | Locked / Required | Core internal mod. Provides Server Config UI and ownership link to LE-MC-HOST website. Cannot be removed. |

## Development Notes

This repository currently holds the public documentation and planned structure for the LEMC mod.

Actual Minecraft (Bedrock / Java) implementation will be added in future updates.

## License

LEMC is proprietary and tied to the LE-MC-HOST platform.
