<p align="center">
  <img src="images/mainn.png" alt="KrobloxDonutSmp2" width="720">
</p>

<h1 align="center">KrobloxDonutSmp2</h1>

<p align="center">
  Free Paper, Purpur, Pufferfish, Spigot, and Folia plugin for DonutSMP-style Minecraft servers.
  Economy, PvP, marketplace, staff tools, menus, and network utilities in one production-focused plugin.
</p>

<p align="center">
  <img alt="Java 21" src="https://img.shields.io/badge/Java-21-007396?style=for-the-badge&logo=openjdk&logoColor=white">
  <img alt="Platform" src="https://img.shields.io/badge/Platform-Paper%20%7C%20Purpur%20%7C%20Pufferfish%20%7C%20Spigot%20%7C%20Folia-2ea44f?style=for-the-badge">
  <img alt="Free" src="https://img.shields.io/badge/Distribution-Free-green?style=for-the-badge">
  <img alt="License" src="https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge">
</p>

## Overview

KrobloxDonutSmp2 is a complete Paper Minecraft server plugin built for DonutSMP-style survival networks. It combines player economy, teams, homes, warps, random teleport, shop, sell, worth, crates, shards, PvP systems, staff utilities, network communication, and GUI-driven workflows into one plugin.

The goal is to reduce the number of separate plugins required for a modern SMP server while keeping configuration, player data, permissions, placeholders, and staff operations consistent across the entire server experience.

## Documentation

This README is the quick reference. The full documentation set lives in [`docs/wiki/`](docs/wiki):

| Page | Contents |
| --- | --- |
| [Home](docs/wiki/Home.md) | Documentation index and technical quick facts |
| [Installation & Setup](docs/wiki/Installation-and-Setup.md) | Server engine setup, SQLite/MySQL/MongoDB storage, and Redis networking |
| [Commands & Permissions](docs/wiki/Commands-and-Permissions.md) | Full command syntax, aliases, and permission nodes |
| [Configuration Reference](docs/wiki/Configuration-Reference.md) | In-depth setup guidance for the larger config files, alongside the per-file `Config-*.yml.md` guides |
| [Economy & Marketplaces](docs/wiki/Economy-and-Marketplaces.md) | Money, shards, shop, sell, Auction House, and Orders |
| [Duels & FFA](docs/wiki/Duels-and-FFA.md) | Duel arenas, queues, rollbacks, and instanced FFA |
| [Ranked PvP Arena](docs/wiki/Ranked-PvP-Arena.md) | Persistent arena, Elo rating, kit editor, and schematic reset |
| [Crates & Spawners](docs/wiki/Crates-and-Spawners.md) | Crate definitions, keys, and Donut-style spawners |
| [Cuboids & Portals](docs/wiki/Cuboids-and-Portals.md) | Region selection, feature zone binding, and portal triggers |
| [Staff & Security](docs/wiki/Staff-and-Security.md) | Staff mode, punishments, detection tools, and moderation |
| [Placeholders & Integrations](docs/wiki/Placeholders-and-Integrations.md) | PlaceholderAPI expansions and third-party plugin support |
| [Localization & Messages](docs/wiki/Localization-and-Messages.md) | 8-language translations, language selection, and message keys |
| [FAQ](docs/wiki/FAQ.md) | Common questions and troubleshooting |
| [Dialog API & older clients](docs/wiki/Dialog-API-and-Older-Clients.md) | Java 1.21.5-and-older clients and Bedrock (Geyser) limits; Quick Buy + Floodgate |

## Highlights

| Area | Included systems |
| --- | --- |
| Platforms | Separate Paper/Purpur/Pufferfish/Spigot and Folia builds with compatibility checks against the latest published APIs |
| Economy | Money, shards, player payments, Vault provider, shop, sell workflows, sell multipliers, worth browser, and sell history |
| Marketplaces | Auction House, Orders board, category filters, claims, delivery, and search |
| Player systems | Teams, friends/follows, homes, warps, private messages, ignore lists, profiles, settings, and custom Ender Chests |
| Progression | Stats, playtime, leaderboards, scoreboards, tablists, bounties, and PlaceholderAPI expansions |
| Teleportation | Spawn, AFK areas, TPA, RTP, portals, cuboid triggers, teleport areas, and safe-location checks |
| PvP | Duels, private invites, map queues, FFA instances, arena rollback, fast crystals, and combat handling |
| Custom content | Crates, virtual keys, Donut-style spawners, amethyst tools, enchantment GUI, filters, and configurable menus |
| Staff and moderation | Staff mode, freeze, vanish, hide/disguise, invsee, ecsee, punishments, alts, reports, helpop, and anvil moderation |
| Detection tools | Spawn-stash bait, fake-player bait, alerts, bypass permissions, and crash protection |
| Network | Redis staff chat and alerts, server-status menus, maintenance routing, Discord webhooks, and Lunar/Apollo support |
| Operations | Automatic configuration sync and backups, feature toggles, setup tools, optimization controls, stats wipe, and guarded server wipe |
| Localization | English, Spanish, Indonesian, Portuguese, German, French, Russian, and Simplified Chinese language packs |

## Screenshots

Feature comparisons (KrobloxDonutSmp2 vs Original DonutSMP):

| KrobloxDonutSmp2 | Original DonutSMP |
| :---: | :---: |
| <img src="images/1.png" alt="TAB - KrobloxDonutSmp2" width="420"> | <img src="images/2.png" alt="TAB - Original DonutSMP" width="420"> |
| <img src="images/3.png" alt="Scoreboards - KrobloxDonutSmp2" width="420"> | <img src="images/4.png" alt="Scoreboards - Original DonutSMP" width="420"> |
| <img src="images/5.png" alt="Dialogues - KrobloxDonutSmp2" width="420"> | <img src="images/6.png" alt="Dialogues - Original DonutSMP" width="420"> |
| <img src="images/7.png" alt="Auction House - KrobloxDonutSmp2" width="420"> | <img src="images/8.png" alt="Auction House - Original DonutSMP" width="420"> |
| <img src="images/9.png" alt="Bounty - KrobloxDonutSmp2" width="420"> | <img src="images/10.png" alt="Bounty - Original DonutSMP" width="420"> |
| <img src="images/11.png" alt="Friends - KrobloxDonutSmp2" width="420"> | <img src="images/12.png" alt="Friends - Original DonutSMP" width="420"> |
| <img src="images/13.png" alt="Homes - KrobloxDonutSmp2" width="420"> | <img src="images/14.png" alt="Homes - Original DonutSMP" width="420"> |
| <img src="images/15.png" alt="Leaderboards - KrobloxDonutSmp2" width="420"> | <img src="images/16.png" alt="Leaderboards - Original DonutSMP" width="420"> |
| <img src="images/17.png" alt="Orders - KrobloxDonutSmp2" width="420"> | <img src="images/18.png" alt="Orders - Original DonutSMP" width="420"> |
| <img src="images/19.png" alt="Pay - KrobloxDonutSmp2" width="420"> | <img src="images/20.png" alt="Pay - Original DonutSMP" width="420"> |
| <img src="images/21.png" alt="Quick Buy - KrobloxDonutSmp2" width="420"> | <img src="images/22.png" alt="Quick Buy - Original DonutSMP" width="420"> |
| <img src="images/23.png" alt="Rank Menu - KrobloxDonutSmp2" width="420"> | <img src="images/24.png" alt="Rank Menu - Original DonutSMP" width="420"> |
| <img src="images/25.png" alt="RTP Queue - KrobloxDonutSmp2" width="420"> | <img src="images/26.png" alt="RTP Queue - Original DonutSMP" width="420"> |
| <img src="images/27.png" alt="Sell - KrobloxDonutSmp2" width="420"> | <img src="images/28.png" alt="Sell - Original DonutSMP" width="420"> |
| <img src="images/29.png" alt="Settings - KrobloxDonutSmp2" width="420"> | <img src="images/30.png" alt="Settings - Original DonutSMP" width="420"> |
| <img src="images/31.png" alt="Shard Shop - KrobloxDonutSmp2" width="420"> | <img src="images/32.png" alt="Shard Shop - Original DonutSMP" width="420"> |
| <img src="images/33.png" alt="Spawners - KrobloxDonutSmp2" width="420"> | <img src="images/34.png" alt="Spawners - Original DonutSMP" width="420"> |
| <img src="images/35.png" alt="Stats - KrobloxDonutSmp2" width="420"> | <img src="images/36.png" alt="Stats - Original DonutSMP" width="420"> |
| <img src="images/37.png" alt="Teleport - KrobloxDonutSmp2" width="420"> | <img src="images/38.png" alt="Teleport - Original DonutSMP" width="420"> |

Feature panels and in-game menus:

|   |   |   |
| :---: | :---: | :---: |
| <img src="images/uds2.png" alt="KrobloxDonutSmp2 feature panel 2" width="270"> | <img src="images/uds3.png" alt="KrobloxDonutSmp2 feature panel 3" width="270"> | <img src="images/uds4.png" alt="KrobloxDonutSmp2 feature panel 4" width="270"> |
| <img src="images/uds5.png" alt="KrobloxDonutSmp2 feature panel 5" width="270"> | <img src="images/uds6.png" alt="KrobloxDonutSmp2 feature panel 6" width="270"> | <img src="images/uds7.png" alt="KrobloxDonutSmp2 feature panel 7" width="270"> |
| <img src="images/uds8.png" alt="KrobloxDonutSmp2 feature panel 8" width="270"> | <img src="images/uds9.png" alt="KrobloxDonutSmp2 feature panel 9" width="270"> | <img src="images/uds10.png" alt="KrobloxDonutSmp2 feature panel 10" width="270"> |
| <img src="images/uds11.png" alt="KrobloxDonutSmp2 feature panel 11" width="270"> | <img src="images/uds12.png" alt="KrobloxDonutSmp2 feature panel 12" width="270"> | <img src="images/uds13.png" alt="KrobloxDonutSmp2 feature panel 13" width="270"> |
| <img src="images/uds14.png" alt="KrobloxDonutSmp2 feature panel 14" width="270"> | <img src="images/uds15.png" alt="KrobloxDonutSmp2 feature panel 15" width="270"> | <img src="images/uds16.png" alt="KrobloxDonutSmp2 feature panel 16" width="270"> |
| <img src="images/uds17.png" alt="KrobloxDonutSmp2 feature panel 17" width="270"> | <img src="images/uds18.png" alt="KrobloxDonutSmp2 feature panel 18" width="270"> | <img src="images/uds19.png" alt="KrobloxDonutSmp2 feature panel 19" width="270"> |

Gameplay clips:

|   |   |
| :---: | :---: |
| <img src="images/gif1.gif" alt="KrobloxDonutSmp2 gameplay clip 1" width="420"> | <img src="images/gif2.gif" alt="KrobloxDonutSmp2 gameplay clip 2" width="420"> |
| <img src="images/gif3.gif" alt="KrobloxDonutSmp2 gameplay clip 3" width="420"> | <img src="images/gif4.gif" alt="KrobloxDonutSmp2 gameplay clip 4" width="420"> |
| <img src="images/gif5.gif" alt="KrobloxDonutSmp2 gameplay clip 5" width="420"> | <img src="images/gif6.gif" alt="KrobloxDonutSmp2 gameplay clip 6" width="420"> |

## Requirements

| Requirement | Notes |
| --- | --- |
| Plugin version | `1.0` |
| Java | Bytecode targets Java 21. The supported Minecraft versions (26.1.2 and newer) require a Java 25 server runtime. |
| Paper / Purpur / Pufferfish / Spigot | Minecraft `26.1.2` through `26.3` |
| Folia | Minecraft `26.1.2` through `26.3` |
| Java client | **1.21.6 or newer.** 1.21.5 and older cannot render Dialog API menus. Block those versions on the proxy or ViaVersion. See [Dialog API & older clients](docs/wiki/Dialog-API-and-Older-Clients.md). |
| Bedrock (Geyser) | **Dialog API menus do not work** (`/menu`, `/ah`, `/pay`, and similar). `/shop` opens a chest grid; pinning items needs **Floodgate** (Geyser alone is not enough). See [Dialog API & older clients](docs/wiki/Dialog-API-and-Older-Clients.md#bedrock-players-geyser--floodgate). |
| Hard dependencies | PlaceholderAPI and ProtocolLib (declared under `depend` in `plugin.yml`; the plugin will not load without them) |
| Default storage | SQLite, bundled through the shaded JDBC driver |
| Alternative storage | MySQL or MongoDB |
| Optional network layer | Redis for cross-server staff chat, alerts, maintenance, reports, helpop, and server status |
| Build environment | Maven available as `mvn`, internet access, and a JDK 21 or newer toolchain (CI builds on JDK 25) |

Required plugins (the server will not enable KrobloxDonutSmp2 without them):

- PlaceholderAPI
- ProtocolLib

Optional integrations:

- LuckPerms
- Vault
- Apollo
- SkinsRestorer
- Multiverse-Core
- floodgate
- Simple Voice Chat (`voicechat`)

The plugin starts without the optional integrations. Their related permission, economy, client, skin, world, voice chat, and Bedrock features activate only when the corresponding plugin is installed.

> [!WARNING]
> **Minecraft 1.21.5 and older clients cannot use this plugin's menus.** KrobloxDonutSmp2 uses Mojang's native [Dialog API](https://minecraft.wiki/w/Dialog), added in Java Edition 1.21.6. Those screens are drawn by the Minecraft client itself. A 1.21.5 (or older) client — typically joining through ViaVersion or ViaBackwards — shows a broken, unusable layout. Commands such as `/ah`, `/menu`, `/homes`, `/pay`, and `/settings` will not present a working screen.
>
> This is not a plugin bug and cannot be fixed here. Other plugins that use Dialog API behave the same way. The chest-menu fallback in `menus.yml` only applies when the **server** lacks Paper's Dialog API (Spigot, or Paper older than 1.21.6). On the Paper versions this plugin supports, dialogs are sent to every player; there is no per-client switch to chest GUIs.
>
> **Require Java clients 1.21.6 or newer.** Block 1.21.5 and below on Velocity, BungeeCord, or ViaVersion. Full write-up: [Dialog API & older clients](docs/wiki/Dialog-API-and-Older-Clients.md).
>
> **Bedrock players (Geyser)** cannot use Java Dialog API screens. That is expected, not a plugin bug. Most hub and economy menus (`/menu`, `/ah`, `/pay`, `/homes` dialog flow, and similar) are Java-only. **`/shop` (Quick Buy)** uses a chest menu Geyser can show; to pin items from Bedrock install **Floodgate** alongside Geyser so the plugin can send Bedrock forms (`QUICK-BUY.BEDROCK` in `shop.yml`). Without Floodgate, pinning falls back to a chest catalogue. Details: [Bedrock players (Geyser / Floodgate)](docs/wiki/Dialog-API-and-Older-Clients.md#bedrock-players-geyser--floodgate).

## Building

Build the project using standard Maven or the build script:

```bat
build.bat
```

Or run Maven directly:

```bash
mvn clean package
```

The build compiles the codebase against the target API and packages a single unified JAR that automatically detects and adapts to Paper, Purpur, Pufferfish, Spigot, or Folia at runtime.

Generated artifact is saved to the `target/` directory:

- `KrobloxDonutSmp2-1.0.jar` (shaded JAR)

## Installation

1. Stop the Minecraft server.
2. Place the plugin jar into the server `plugins/` directory.
3. Start the server once so the default configuration files are generated.
4. Configure storage in `database.yml`.
5. Review the core gameplay files such as `config.yml`, `menus.yml`, `shop.yml`, `worth.yml`, `rtp.yml`, and `languages/<locale>.yml`.
6. Restart the server after first setup.

For production networks, MySQL plus Redis is recommended. For a single-server setup, SQLite is usually enough.

> [!WARNING]
> Do not share private customer files, database credentials, Discord tokens, Redis passwords, or other sensitive server data.

## Configuration

| File | Purpose |
| --- | --- |
| `config.yml` | Language selection, feature toggles, locations, portals, chat, AFK, cuboid binds, combat, crystals, shards, tablist, optimization, and general gameplay |
| `languages/*.yml` | Player-facing command, gameplay, moderation, economy, teleport, menu, and system text |
| `death-messages.yml` | Death-message rules and message templates |
| `menus.yml` | Shared GUI layouts for teams, homes, profiles, settings, leaderboards, shops, staff tools, rules, servers, and other menus |
| `dialog.yml` | 1.21.6+ dialog screens: the main menu grid, settings categories, pay, stats, leaderboards, homes, friends, teleport, the RTP queue prompt, and the generated ESC-screen datapack |
| `scoreboard.yml` | Modern and legacy sidebar layouts, title, lines, refresh behavior, and display rules |
| `shop.yml` | Money and shard shop categories, items, prices, permissions, currencies, and command rewards |
| `sounds.yml` | Sound effects for menus, commands, teleportation, shops, shards, boosters, and custom systems |
| `pvp.yml` | Ranked PvP arena, Elo rating, kits, boundary, broadcasts, and schematic reset |
| `rtp.yml` | Random teleport worlds, radius, cooldowns, safety checks, denied worlds, messages, and GUI |
| `worth.yml` | Sell values, worth display, container handling, browser categories, and blocked items |
| `amethyst-tools.yml` | Amethyst tool types, durations, permissions, effects, items, actions, and messages |
| `ender-chest.yml` | Custom Ender Chest size, behavior, ecsee access, layout, and messages |
| `invsee.yml` | Inventory inspection behavior, layout, permissions, and messages |
| `freeze.yml` | Freeze behavior, permissions, alerts, inventory handling, and messages |
| `auction-house.yml` | Listing limits, pricing, claims, restrictions, sorting, categories, and Auction House GUI |
| `orders.yml` | Order limits, pricing, delivery, matching, filters, sorting, Bedrock input, network behavior, and GUI |
| `enchantments.yml` | Enchantment GUI and item-specific enchantment options |
| `filter.yml` | Item category filters used by marketplace and inventory workflows |
| `duels.yml` | Duel maps, world borders, queues, countdowns, cross-server options, arena settings, rules, and GUI |
| `ffa.yml` | FFA queue, arena rules, rollback, player-state handling, and arena definitions |
| `crates.yml` | Crate definitions, keys, rewards, animations, holograms, particles, and settings |
| `spawners.yml` | Donut-style spawner types, drops, storage, and GUI |
| `spawn-stash.yml` | Temporary bait-stash types, detection rules, alerts, cleanup, and messages |
| `network.yml` | Redis network identity, staff chat, reports, helpop, server status, and maintenance routing |
| `staff-mode.yml` | Staff-mode permissions, hotbar items, vanish, better view, staff list, fake players, and menus |
| `hide.yml` | Identity scrambling, aliases, disguises, skins, cooldowns, bypass rules, GUI, and messages |
| `database.yml` | SQLite, MySQL, MongoDB, and Redis connection settings |
| `server-wipe.yml` | Guarded wipe targets, protected worlds, confirmation token lifetime, backups, and messages |
| `discord.yml` | Discord webhook endpoints and event-specific webhook controls |
| `anvil-moderation.yml` | Banned anvil words, punishments, and per-player moderation data |
| `offenses.yml` | Preset offense rules, punishment types, and durations used by `/offend` |

Language files are stored under `languages/`:

- `en_US.yml`
- `es_ES.yml`
- `id_ID.yml`
- `pt_BR.yml`
- `de_DE.yml`
- `fr_FR.yml`
- `ru_RU.yml`
- `zh_CN.yml`

On startup and reload, missing bundled configuration paths are merged into existing files. Existing files are backed up under `config-backups/` before an automatic update. Live crate definitions, duel/FFA arenas, and deployment-specific network server entries are treated as user-managed data and are not restored after removal.

## Commands

Commands can be disabled through their related feature toggle. Arguments in `<angle brackets>` are required; arguments in `[square brackets]` are optional. Every command has a dedicated permission node registered in `plugin.yml`. Most follow the `krobloxdonutsmp2.command.<command>` pattern; a few staff commands use a `krobloxdonutsmp2.staff.*` node instead, as listed below.

| Command | Aliases | Usage | Permission Node |
| --- | --- | --- | --- |
| `/addmoney` | - | `/addmoney <player> <amount>` | `krobloxdonutsmp2.command.addmoney` |
| `/addshards` | - | `/addshards <player> <amount>` | `krobloxdonutsmp2.command.addshards` |
| `/afk` | - | `/afk` | `krobloxdonutsmp2.command.afk` |
| `/alts` | - | `/alts <player>` | `krobloxdonutsmp2.command.alts` |
| `/amethysttool` | - | `/amethysttool give <player> <type> [duration]` or `/amethysttool reload` | `krobloxdonutsmp2.command.amethysttool` |
| `/amod` | - | `/amod <add\|reload>` | `krobloxdonutsmp2.command.amod` |
| `/arena` | `/duelarena` | `/arena <create\|delete\|setpos1\|setpos2\|setreturn\|setdisplay\|enable\|disable\|queue\|list\|reload>` | `krobloxdonutsmp2.command.arena` |
| `/auctionhouse` | `/ah` | `/auctionhouse [sell\|my\|claims\|cancel\|limit\|fastbuy\|fastsell\|reload]` | `krobloxdonutsmp2.command.auctionhouse` |
| `/balance` | `/bal`, `/money` | `/balance [player]` | `krobloxdonutsmp2.command.balance` |
| `/ban` | - | `/ban <player> [reason]` | `krobloxdonutsmp2.command.ban` |
| `/blacklist` | - | `/blacklist <player> [reason]` | `krobloxdonutsmp2.command.blacklist` |
| `/bounty` | - | `/bounty <add\|set\|info\|list> [player] [amount]` | `krobloxdonutsmp2.command.bounty` |
| `/chat` | - | `/chat <help\|mute\|unmute\|delay\|clear>` | `krobloxdonutsmp2.command.chat` |
| `/chatlog` | - | `/chatlog [player]` | `krobloxdonutsmp2.command.chatlog` |
| `/clearlag` | - | `/clearlag` | `krobloxdonutsmp2.command.clearlag` |
| `/crate` | - | `/crate <create\|delete\|type\|open\|keys\|reload\|key\|take\|set\|keyall\|add\|edit\|remove\|bind\|unbind\|info>` | `krobloxdonutsmp2.command.crate` |
| `/crates` | - | `/crates` | `krobloxdonutsmp2.command.crates` |
| `/create` | - | `/create <invite\|friends> <player> [map]` | `krobloxdonutsmp2.command.create` |
| `/cuboid` | - | `/cuboid <wand\|create\|delete\|list\|setspawn\|delspawn\|bind <cuboid> <spawn\|shard\|rtp-zone\|rtp-queue> <true\|false>\|reload>` | `krobloxdonutsmp2.command.cuboid` |
| `/delhome` | - | `/delhome <name>` | `krobloxdonutsmp2.command.delhome` |
| `/delwarp` | - | `/delwarp <name>` | `krobloxdonutsmp2.command.delwarp` |
| `/discord` | - | `/discord` | `krobloxdonutsmp2.command.discord` |
| `/disguise` | - | `/disguise [player-name\|url]` or `/disguise <alias> <player-name\|url>` | `krobloxdonutsmp2.command.disguise` |
| `/draw` | - | `/draw` | `krobloxdonutsmp2.command.draw` |
| `/duel` | - | `/duel [player\|accept\|deny\|claims\|reload]` | `krobloxdonutsmp2.command.duel` |
| `/ecsee` | - | `/ecsee <player>` | `krobloxdonutsmp2.command.ecsee` |
| `/enderchest` | `/ec` | `/enderchest [reload]` | `krobloxdonutsmp2.command.enderchest` |
| `/fakeplayer` | `/fplayer` | `/fakeplayer` | `krobloxdonutsmp2.command.fakeplayer` |
| `/feed` | - | `/feed [player]` | `krobloxdonutsmp2.command.feed` |
| `/ffa` | - | `/ffa [join\|reload\|arena ...]` | `krobloxdonutsmp2.command.ffa` |
| `/ffaarena` | - | `/ffaarena <create\|delete\|setpos\|setdisplay\|settings\|enable\|disable\|list\|reload>` | `krobloxdonutsmp2.command.ffaarena` |
| `/ffastats` | - | `/ffastats [player]` | `krobloxdonutsmp2.command.ffastats` |
| `/findplayer` | `/fp` | `/findplayer <player>` | `krobloxdonutsmp2.command.findplayer` |
| `/fly` | - | `/fly [player]` | `krobloxdonutsmp2.command.fly` |
| `/flyspeed` | `/fs` | `/flyspeed <1-10> [player]` | `krobloxdonutsmp2.command.flyspeed` |
| `/freeze` | - | `/freeze <player>` or `/freeze reload` | `krobloxdonutsmp2.command.freeze` |
| `/friend` | - | `/friend` | `krobloxdonutsmp2.command.friend` |
| `/friends` | - | `/friends [list\|follow\|remove\|search\|following\|followers\|friends]` | `krobloxdonutsmp2.command.friends` |
| `/gamemode` | `/gm`, `/gmc`, `/gms`, `/gma`, `/gmsp` | `/gamemode <mode> [player]` | `krobloxdonutsmp2.command.gamemode` |
| `/god` | `/godmode` | `/god [player]` | `krobloxdonutsmp2.staff.god` |
| `/heal` | - | `/heal [player]` | `krobloxdonutsmp2.command.heal` |
| `/help` | - | `/help` | `krobloxdonutsmp2.command.help` |
| `/helpop` | - | `/helpop <message>` | `krobloxdonutsmp2.command.helpop` |
| `/hide` | - | `/hide [status\|scramble\|remove\|check <player>\|list]` | `krobloxdonutsmp2.command.hide` |
| `/home` | - | `/home [name]` | `krobloxdonutsmp2.command.home` |
| `/homes` | - | `/homes` | `krobloxdonutsmp2.command.homes` |
| `/ignore` | - | `/ignore <player\|list>` | `krobloxdonutsmp2.command.ignore` |
| `/invsee` | `/inventorysee` | `/invsee <player>` or `/invsee reload` | `krobloxdonutsmp2.command.invsee` |
| `/keys` | - | `/keys` | `krobloxdonutsmp2.command.keys` |
| `/kick` | - | `/kick <player> [reason]` | `krobloxdonutsmp2.command.kick` |
| `/kill` | - | `/kill` | `krobloxdonutsmp2.command.kill` |
| `/leaderboard` | `/lb`, `/top`, `/leaderboards`, `/baltop` | `/leaderboard [type]` | `krobloxdonutsmp2.command.leaderboard` |
| `/leave` | - | `/leave` | `krobloxdonutsmp2.command.leave` |
| `/logs` | - | `/logs` | `krobloxdonutsmp2.command.logs` |
| `/maintenance` | - | `/maintenance <on [duration]\|off\|status\|setlobby [server]>` | `krobloxdonutsmp2.command.maintenance` |
| `/menu` | `/donut`, `/dialog` | `/menu` | `krobloxdonutsmp2.command.menu` |
| `/meta` | `/farmingmeta` | `/meta` | `krobloxdonutsmp2.command.meta` |
| `/msg` | `/message`, `/tell`, `/whisper`, `/w` | `/msg <player> <message>` | `krobloxdonutsmp2.command.msg` |
| `/mute` | - | `/mute <player> [reason]` | `krobloxdonutsmp2.command.mute` |
| `/nightvision` | `/nv` | `/nightvision` | `krobloxdonutsmp2.command.nightvision` |
| `/offend` | - | `/offend <player> <reason> [time]` | `krobloxdonutsmp2.staff.punishments.offend` |
| `/orders` | - | `/orders [my\|collect\|reload\|search query]` | `krobloxdonutsmp2.command.orders` |
| `/pay` | - | `/pay <player> <amount>` | `krobloxdonutsmp2.command.pay` |
| `/phantom` | - | `/phantom` | `krobloxdonutsmp2.command.phantom` |
| `/ping` | - | `/ping [player]` | `krobloxdonutsmp2.command.ping` |
| `/playerunwipe` | `/punwipe`, `/unwipe` | `/playerunwipe <player> [confirm]` | `krobloxdonutsmp2.command.playerunwipe` |
| `/playerwipe` | `/pwipe`, `/wipe` | `/playerwipe <player> [confirm]` | `krobloxdonutsmp2.command.playerwipe` |
| `/playtime` | `/pt` | `/playtime [player]` | `krobloxdonutsmp2.command.playtime` |
| `/pm` | `/togglepm`, `/privatemessages` | `/pm` | `krobloxdonutsmp2.command.pm` |
| `/portalmanager` | - | `/portalmanager <list\|info\|create\|delete\|setcuboid\|setdestination\|setdisplay\|toggle\|setpriority\|sethologramhere>` | `krobloxdonutsmp2.command.portalmanager` |
| `/profileviewer` | `/pv` | `/profileviewer <player>` | `krobloxdonutsmp2.command.profileviewer` |
| `/punishments` | `/phistory` | `/punishments <player>` | `krobloxdonutsmp2.command.punishments` |
| `/pvp` | - | `/pvp [join\|leave\|kit\|stats\|top\|queue\|leaderboard\|history\|assign\|wand\|create\|setspawn\|setspawn2\|setlobby\|setboundary\|schematic\|reset\|reload]` | `krobloxdonutsmp2.command.pvp` |
| `/queue` | - | `/queue [join\|leave] [map]` | `krobloxdonutsmp2.command.queue` |
| `/randomteleport` | `/randomtp` | `/randomteleport` | `krobloxdonutsmp2.command.randomteleport` |
| `/ranks` | `/rank` | `/ranks` | `krobloxdonutsmp2.command.ranks` |
| `/removemoney` | - | `/removemoney <player> <amount>` | `krobloxdonutsmp2.command.removemoney` |
| `/removeshards` | - | `/removeshards <player> <amount>` | `krobloxdonutsmp2.command.removeshards` |
| `/rename` | - | `/rename <name...\|reset>` | `krobloxdonutsmp2.command.rename` |
| `/renamehome` | - | `/renamehome <old> <new>` | `krobloxdonutsmp2.command.renamehome` |
| `/reply` | `/r` | `/reply <message>` | `krobloxdonutsmp2.command.reply` |
| `/report` | - | `/report <player> <reason>` | `krobloxdonutsmp2.command.report` |
| `/rtp` | - | `/rtp [world]` | `krobloxdonutsmp2.command.rtp` |
| `/rtpq` | `/rtpqueue` | `/rtpq [join\|leave]` | `krobloxdonutsmp2.command.rtpq` |
| `/rules` | - | `/rules` | `krobloxdonutsmp2.command.rules` |
| `/safety` | - | `/safety [reload\|add [player]]` | `krobloxdonutsmp2.command.safety` |
| `/seehomes` | `/homesee` | `/seehomes <player>` | `krobloxdonutsmp2.command.seehomes` |
| `/sell` | - | `/sell` | `krobloxdonutsmp2.command.sell` |
| `/sellall` | - | `/sellall` | `krobloxdonutsmp2.command.sellall` |
| `/sellhand` | - | `/sellhand [amount]` | `krobloxdonutsmp2.command.sellhand` |
| `/sellhistory` | - | `/sellhistory` | `krobloxdonutsmp2.command.sellhistory` |
| `/sellmulti` | - | `/sellmulti [category]` | `krobloxdonutsmp2.command.sellmulti` |
| `/sellmultiplier` | - | `/sellmultiplier [category]` | `krobloxdonutsmp2.command.sellmulti` |
| `/sellprogress` | - | `/sellprogress [category]` | `krobloxdonutsmp2.command.sellprogress` |
| `/servers` | - | `/servers` | `krobloxdonutsmp2.command.servers` |
| `/serverwipe` | - | `/serverwipe <preview\|prepare\|confirm\|cancel\|status>` | `krobloxdonutsmp2.command.serverwipe` |
| `/setafk` | - | `/setafk` | `krobloxdonutsmp2.command.setafk` |
| `/sethome` | - | `/sethome [name]` | `krobloxdonutsmp2.command.sethome` |
| `/setmoney` | - | `/setmoney <player> <amount>` | `krobloxdonutsmp2.command.setmoney` |
| `/setshards` | - | `/setshards <player> <amount>` | `krobloxdonutsmp2.command.setshards` |
| `/setspawn` | - | `/setspawn` | `krobloxdonutsmp2.command.setspawn` |
| `/settings` | - | `/settings` | `krobloxdonutsmp2.command.settings` |
| `/setwarp` | - | `/setwarp <name>` | `krobloxdonutsmp2.command.setwarp` |
| `/shardpay` | - | `/shardpay <player> <amount>` | `krobloxdonutsmp2.command.shardpay` |
| `/shards` | - | `/shards [player]` or `/shards everywhere <status\|debug> [player]` | `krobloxdonutsmp2.command.shards` |
| `/shardshop` | - | `/shardshop` | `krobloxdonutsmp2.command.shardshop` |
| `/shop` | - | `/shop [reload]` | `krobloxdonutsmp2.command.shop` |
| `/social` | `/media` | `/social` | `krobloxdonutsmp2.command.social` |
| `/spawn` | - | `/spawn` | `krobloxdonutsmp2.command.spawn` |
| `/spawner` | `/spawners` | `/spawner [give\|info\|panel\|reload\|remove\|split]` | `krobloxdonutsmp2.command.spawner` |
| `/spawnstash` | `/stash` | `/spawnstash [type\|spawn\|list\|remove\|reload]` | `krobloxdonutsmp2.command.spawnstash` |
| `/staffchat` | `/sc` | `/staffchat <message>` | `krobloxdonutsmp2.command.staffchat` |
| `/stafflist` | - | `/stafflist` | `krobloxdonutsmp2.command.stafflist` |
| `/staffmode` | `/staff` | `/staffmode [player\|reload]` | `krobloxdonutsmp2.command.staffmode` |
| `/stats` | - | `/stats [player]` | `krobloxdonutsmp2.command.stats` |
| `/store` | - | `/store` | `krobloxdonutsmp2.command.store` |
| `/team` | - | `/team <create\|disband\|invite\|kick\|join\|leave\|home\|sethome\|delhome\|chat\|info\|pvp>` | `krobloxdonutsmp2.command.team` |
| `/teleport` | `/tp`, `/tphere`, `/tpall` | `/teleport <player\|here <player>\|all\|top\|x y z [world]>` | `krobloxdonutsmp2.command.teleport` |
| `/tempban` | - | `/tempban <player> <time> [reason]` | `krobloxdonutsmp2.command.tempban` |
| `/tempmute` | - | `/tempmute <player> <time> [reason]` | `krobloxdonutsmp2.command.tempmute` |
| `/topsell` | `/sellstats` | `/topsell [gui\|items\|volume\|sellers\|export]` | `krobloxdonutsmp2.command.topsell` |
| `/tpa` | - | `/tpa <player>` | `krobloxdonutsmp2.command.tpa` |
| `/tpacancel` | - | `/tpacancel` | `krobloxdonutsmp2.command.tpacancel` |
| `/tpaccept` | - | `/tpaccept [player]` | `krobloxdonutsmp2.command.tpaccept` |
| `/tpadeny` | - | `/tpadeny [player]` | `krobloxdonutsmp2.command.tpadeny` |
| `/tpahere` | - | `/tpahere <player>` | `krobloxdonutsmp2.command.tpahere` |
| `/tpahereauto` | - | `/tpahereauto` | `krobloxdonutsmp2.command.tpahereauto` |
| `/tpauto` | - | `/tpauto` | `krobloxdonutsmp2.command.tpauto` |
| `/twitter` | - | `/twitter` | `krobloxdonutsmp2.command.twitter` |
| `/krobloxdonutsmp2` | `/kds2`, `/kdsmp2` | `/krobloxdonutsmp2 <reload\|statswipe\|optimize\|setup\|features\|maintenance>` | `krobloxdonutsmp2.command.krobloxdonutsmp2` |
| `/unban` | `/pardon` | `/unban <player> [reason]` | `krobloxdonutsmp2.command.unban` |
| `/unblacklist` | - | `/unblacklist <player> [reason]` | `krobloxdonutsmp2.command.unblacklist` |
| `/unignore` | - | `/unignore <player>` | `krobloxdonutsmp2.command.unignore` |
| `/unmute` | - | `/unmute <player> [reason]` | `krobloxdonutsmp2.command.unmute` |
| `/vanish` | - | `/vanish` | `krobloxdonutsmp2.command.vanish` |
| `/vcmute` | - | `/vcmute <player> [reason]` | `krobloxdonutsmp2.staff.vcmute` |
| `/vcunmute` | - | `/vcunmute <player> [reason]` | `krobloxdonutsmp2.staff.vcunmute` |
| `/voicechatconsent` | `/vcconsent`, `/voiceconsent` | `/voicechatconsent [revoke]` | `krobloxdonutsmp2.command.voicechatconsent` |
| `/warn` | - | `/warn <player> [reason]` | `krobloxdonutsmp2.command.warn` |
| `/warp` | - | `/warp [name]` | `krobloxdonutsmp2.command.warp` |
| `/warpmanager` | - | `/warpmanager <create\|delete\|list> [name]` | `krobloxdonutsmp2.command.warpmanager` |
| `/worth` | `/prices` | `/worth [hand\|reload]` | `krobloxdonutsmp2.command.worth` |

Temporary punishment durations accept combined values such as `30s`, `15m`, `2h`, `5d`, or `5d 15m 30s`.

Running `/baltop` with no arguments opens the money leaderboard directly instead of the leaderboard type menu.

## Permissions

`true` means the permission is granted by default to all players, `op` means it defaults to server operators, and `false` means it must be granted explicitly. `krobloxdonutsmp2.admin` is the main admin parent node, and `krobloxdonutsmp2.command.*` grants access to all plugin commands.

### Main Parent Nodes

| Permission Node | Default | Description |
| --- | --- | --- |
| `krobloxdonutsmp2.admin` | `op` | Main admin parent node giving access to administrative commands, reload, wipe, and management systems |
| `krobloxdonutsmp2.command.*` | `op` | Grants access to execute all KrobloxDonutSmp2 commands |
| `krobloxdonutsmp2.staff.mode` | `op` | Staff moderation mode parent node (vanish, betterview, randomtp, staff list, tools) |
| `krobloxdonutsmp2.staff.alerts.receive` | `op` | Parent node for receiving staff alerts (`helpop` and `report`) |
| `krobloxdonutsmp2.staff.punishments.create` | `op` | Parent node for issuing punishments (`warn`, `kick`, `ban`, `mute`, `blacklist`) |
| `krobloxdonutsmp2.staff.punishments.remove` | `op` | Parent node for removing active punishments (`unban`, `unmute`, `unblacklist`) |

### System & Staff Permissions

| Permission | Default | Description |
| --- | --- | --- |
| `anvilmod.admin` | `op` | Admin access for anvil word moderation |
| `safety.add` | `op` | Add players to safety check bypass list |
| `safety.reload` | `op` | Reload safety configuration |
| `safety.use` | `true` | Standard safety system permission |
| `krobloxdonutsmp2.admin.addmoney` | `op` | Add money to player balances |
| `krobloxdonutsmp2.admin.amethysttool` | `op` | Give and reload amethyst tools |
| `krobloxdonutsmp2.admin.auctionhouse` | `op` | Reload and manage Auction House settings |
| `krobloxdonutsmp2.admin.chatlog` | `op` | Browse logged public chat messages |
| `krobloxdonutsmp2.admin.clearlag` | `op` | Trigger lag clear manually |
| `krobloxdonutsmp2.admin.crate` | `op` | Manage crate balances, chest bindings, and settings |
| `krobloxdonutsmp2.admin.crate.keyall` | `op` | Trigger key-all rewards manually |
| `krobloxdonutsmp2.admin.crate.reload` | `op` | Reload crate configuration |
| `krobloxdonutsmp2.admin.cuboid` | `op` | Create, bind, and manage cuboid regions |
| `krobloxdonutsmp2.admin.delwarp` | `op` | Delete public warp points |
| `krobloxdonutsmp2.admin.duels` | `op` | Manage duel settings and arenas |
| `krobloxdonutsmp2.admin.ecsee` | `op` | View other players' Ender Chest contents |
| `krobloxdonutsmp2.admin.enderchest` | `op` | Reload Ender Chest settings |
| `krobloxdonutsmp2.admin.features` | `op` | Access and toggle runtime feature switches |
| `krobloxdonutsmp2.admin.ffa` | `op` | Manage FFA arenas and settings |
| `krobloxdonutsmp2.admin.freeze` | `op` | Reload freeze settings |
| `krobloxdonutsmp2.admin.invsee` | `op` | Reload Invsee settings |
| `krobloxdonutsmp2.admin.logs` | `op` | View command log history |
| `krobloxdonutsmp2.admin.maintenance` | `op` | Manage maintenance mode |
| `krobloxdonutsmp2.admin.maintenance.bypass` | `op` | Join server while maintenance mode is enabled |
| `krobloxdonutsmp2.admin.optimize` | `op` | Access runtime optimization controls |
| `krobloxdonutsmp2.admin.orders` | `op` | Manage and reload Orders board settings |
| `krobloxdonutsmp2.admin.playerunwipe` | `op` | Preview and restore a wiped player's stored data |
| `krobloxdonutsmp2.admin.playerwipe` | `op` | Preview and wipe a single player's stored data |
| `krobloxdonutsmp2.admin.portalmanager` | `op` | Create, display, and manage RTP portals |
| `krobloxdonutsmp2.admin.punishments.exempt` | `op` | Cannot be punished by staff who lack the exempt bypass |
| `krobloxdonutsmp2.admin.punishments.exempt.bypass` | `op` | Punish players who are exempt from being punished |
| `krobloxdonutsmp2.admin.pvp` | `op` | Manage the ranked PvP arena and its kits |
| `krobloxdonutsmp2.admin.reload` | `op` | Reload all KrobloxDonutSmp2 configurations |
| `krobloxdonutsmp2.admin.removemoney` | `op` | Remove money from player balances |
| `krobloxdonutsmp2.admin.sellstats` | `op` | View top sell statistics and economy metrics |
| `krobloxdonutsmp2.admin.serverwipe` | `op` | Execute guarded server wipe operations |
| `krobloxdonutsmp2.admin.setmoney` | `op` | Set player money balances |
| `krobloxdonutsmp2.admin.setup` | `op` | Use interactive setup status and tools |
| `krobloxdonutsmp2.admin.setwarp` | `op` | Set public warp points |
| `krobloxdonutsmp2.admin.shards` | `op` | Inspect Shards Everywhere status |
| `krobloxdonutsmp2.admin.shop` | `op` | Reload shop settings |
| `krobloxdonutsmp2.admin.spawner` | `op` | Give and manage Donut-style spawners |
| `krobloxdonutsmp2.admin.spawnstash` | `op` | Manage bait spawn stashes |
| `krobloxdonutsmp2.admin.staffmode` | `op` | Reload Staff Mode settings |
| `krobloxdonutsmp2.admin.statswipe` | `op` | Execute player stats wipe |
| `krobloxdonutsmp2.admin.teleportareas.delete` | `op` | Delete configured teleport areas |
| `krobloxdonutsmp2.admin.warpmanager` | `op` | Manage public warps |
| `krobloxdonutsmp2.admin.worth` | `op` | Reload sell/worth settings |
| `krobloxdonutsmp2.command.flyspeed` | `op` | Use `/flyspeed` |
| `krobloxdonutsmp2.command.offend` | `op` | Use `/offend` (parent of `krobloxdonutsmp2.staff.punishments.offend`) |

### Staff Moderation & Alert Permissions

| Permission | Default | Description |
| --- | --- | --- |
| `krobloxdonutsmp2.staff.alerts.bypass-cooldown` | `op` | Bypass report and helpop cooldowns |
| `krobloxdonutsmp2.staff.alerts.receive` | `op` | Receive helpop and report staff alerts |
| `krobloxdonutsmp2.staff.alts` | `op` | Check IP history and alt accounts |
| `krobloxdonutsmp2.staff.chat.bypass.delay` | `op` | Bypass global chat delay |
| `krobloxdonutsmp2.staff.chat.bypass.filter` | `op` | Bypass global chat filter |
| `krobloxdonutsmp2.staff.chat.bypass.mute` | `op` | Bypass global chat mute |
| `krobloxdonutsmp2.staff.chat.clear` | `op` | Clear chat screen visually |
| `krobloxdonutsmp2.staff.chat.delay` | `op` | Set global chat delay |
| `krobloxdonutsmp2.staff.chat.mute` | `op` | Mute global chat |
| `krobloxdonutsmp2.staff.chat.unmute` | `op` | Unmute global chat |
| `krobloxdonutsmp2.staff.chat.use` | `op` | Send and receive staff chat |
| `krobloxdonutsmp2.staff.fakeplayer` | `op` | Spawn fake player bait entities |
| `krobloxdonutsmp2.staff.fakeplayer.alert` | `op` | Receive fake player bait attack alerts |
| `krobloxdonutsmp2.staff.fakeplayer.bypass` | `op` | Bypass fake player bait triggers |
| `krobloxdonutsmp2.staff.feed` | `op` | Feed players |
| `krobloxdonutsmp2.staff.fly` | `op` | Toggle flight mode |
| `krobloxdonutsmp2.staff.flyspeed` | `op` | Adjust flying speed for yourself or another player |
| `krobloxdonutsmp2.staff.freeze` | `op` | Freeze/unfreeze players for inspection |
| `krobloxdonutsmp2.staff.freeze.alert` | `op` | Receive player freeze alerts |
| `krobloxdonutsmp2.staff.freeze.exempt` | `op` | Exempt from being frozen by staff |
| `krobloxdonutsmp2.staff.gamemode` | `op` | Change own gamemode |
| `krobloxdonutsmp2.staff.gamemode.others` | `op` | Change other players' gamemodes |
| `krobloxdonutsmp2.staff.god` | `op` | Toggle god mode |
| `krobloxdonutsmp2.staff.heal` | `op` | Heal players |
| `krobloxdonutsmp2.staff.helpop.receive` | `op` | Receive helpop request alerts |
| `krobloxdonutsmp2.staff.invsee` | `op` | Inspect player inventories |
| `krobloxdonutsmp2.staff.invsee.modify` | `op` | Modify player inventories in invsee |
| `krobloxdonutsmp2.staff.mode.betterview` | `op` | Toggle better view in staff mode |
| `krobloxdonutsmp2.staff.mode.others` | `op` | Toggle staff mode for other players |
| `krobloxdonutsmp2.staff.mode.randomtp` | `op` | Random teleport in staff mode |
| `krobloxdonutsmp2.staff.mode.seevanished` | `op` | See vanished staff members |
| `krobloxdonutsmp2.staff.mode.stafflist` | `op` | Open online staff list |
| `krobloxdonutsmp2.staff.mode.vanish` | `op` | Toggle vanish in staff mode |
| `krobloxdonutsmp2.staff.profileviewer` | `op` | View player profiles and homes |
| `krobloxdonutsmp2.staff.seehomes` | `op` | Browse any player's homes and teleport to them |
| `krobloxdonutsmp2.staff.punishments.ban` | `false` | Apply ban and tempban punishments |
| `krobloxdonutsmp2.staff.punishments.blacklist` | `false` | Apply blacklist punishments |
| `krobloxdonutsmp2.staff.punishments.delete` | `op` | Delete punishment logs from GUI |
| `krobloxdonutsmp2.staff.punishments.mute` | `false` | Apply mute and tempmute punishments |
| `krobloxdonutsmp2.staff.punishments.offend` | `op` | Apply preset offense punishments from `offenses.yml` |
| `krobloxdonutsmp2.staff.punishments.unban` | `false` | Remove active bans |
| `krobloxdonutsmp2.staff.punishments.unblacklist` | `false` | Remove active blacklists |
| `krobloxdonutsmp2.staff.punishments.unmute` | `false` | Remove active mutes |
| `krobloxdonutsmp2.staff.punishments.view` | `op` | View punishment history |
| `krobloxdonutsmp2.staff.rename` | `op` | Rename items |
| `krobloxdonutsmp2.staff.report.receive` | `op` | Receive player report alerts |
| `krobloxdonutsmp2.staff.spawnstash` | `op` | Place and inspect spawn stash bait |
| `krobloxdonutsmp2.staff.spawnstash.alert` | `op` | Receive spawn stash trigger alerts |
| `krobloxdonutsmp2.staff.spawnstash.bypass` | `op` | Bypass spawn stash detection |
| `krobloxdonutsmp2.staff.teleport` | `op` | Access staff teleport tools |
| `krobloxdonutsmp2.staff.vcmute` | `false` | Apply voice chat mute punishments |
| `krobloxdonutsmp2.staff.vcunmute` | `false` | Remove voice chat mute punishments |

### Player & Feature Permissions

| Permission | Default | Description |
| --- | --- | --- |
| `donutauction.use` / `krobloxdonutsmp2.auctionhouse.use` | `true` / `false` | Open Auction House GUI |
| `donutauction.buy` / `krobloxdonutsmp2.auctionhouse.buy` | `true` / `false` | Buy items on Auction House |
| `donutauction.sell` / `krobloxdonutsmp2.auctionhouse.sell` | `true` / `false` | Sell items on Auction House |
| `donutauction.my` / `krobloxdonutsmp2.auctionhouse.my` | `true` / `false` | View own listings on Auction House |
| `donutauction.claims` / `krobloxdonutsmp2.auctionhouse.claims` | `true` / `false` | Collect claims from Auction House |
| `donutauction.cancel` / `krobloxdonutsmp2.auctionhouse.cancel` | `true` / `false` | Cancel own listings on Auction House |
| `donutauction.limit` / `krobloxdonutsmp2.auctionhouse.limit` | `true` / `false` | Check listing limits on Auction House |
| `donutauction.fastbuy` / `krobloxdonutsmp2.auctionhouse.fastbuy` | `false` / `op` | Fast buy command access |
| `donutauction.fastsell` / `krobloxdonutsmp2.auctionhouse.fastsell` | `false` / `op` | Fast sell command access |
| `krobloxdonutsmp2.command.friend` | `true` | Use `/friend` |
| `krobloxdonutsmp2.command.sellmulti` | `true` | Open the sell multiplier menu (`/sellmulti`, `/sellmultiplier`) |
| `krobloxdonutsmp2.command.sellprogress` | `true` | Open the sell multiplier progress menu (`/sellprogress`) |
| `krobloxdonutsmp2.enderchest` | `true` | Open custom Ender Chest |
| `krobloxdonutsmp2.friends` | `true` | Friends and follow system |
| `krobloxdonutsmp2.helpop` | `true` | Use `/helpop` to request staff help |
| `krobloxdonutsmp2.hide.admin` | `op` | Manage and inspect player disguises |
| `krobloxdonutsmp2.hide.bypass` | `op` | Bypass disguise restrictions |
| `krobloxdonutsmp2.hide.disguise` | `op` | Change skin and disguise alias |
| `krobloxdonutsmp2.hide.scramble` | `op` | Scramble public username |
| `krobloxdonutsmp2.ignore` | `true` | Ignore and unignore players |
| `krobloxdonutsmp2.ignore.bypass` | `op` | Bypass private message ignore filter |
| `krobloxdonutsmp2.message` | `true` | Send and reply to private messages |
| `krobloxdonutsmp2.message.bypass-disabled` | `op` | Bypass recipient disabled PMs |
| `krobloxdonutsmp2.message.toggle` | `true` | Toggle private messages on/off |
| `krobloxdonutsmp2.report` | `true` | Report players to online staff |
| `krobloxdonutsmp2.servers` | `false` | View network server status GUI |
| `krobloxdonutsmp2.shards.everywhere` | `false` | Receive passive Shards Everywhere rewards |
| `krobloxdonutsmp2.shardshop` | `true` | Open Shard Shop GUI |
| `krobloxdonutsmp2.spawner.bypass` | `false` | Break spawners without a Silk Touch pickaxe while `REQUIRE_SILK_TOUCH` is enabled |
| `media` | `false` | Display configurable Media tablist badge (requires explicit LuckPerms assignment, not auto-granted to OP) |
| `rank.media` | `false` | Display configurable Media tablist badge legacy alias |
| `rank.media.plus` | `false` | Display configurable Media+ tablist badge (requires explicit LuckPerms assignment, not auto-granted to OP) |
| `rank.media.include` | `false` | Include player in media badge handling (requires explicit LuckPerms assignment, not auto-granted to OP) |

## Placeholders

KrobloxDonutSmp2 includes built-in [PlaceholderAPI](https://placeholderapi.com/) expansion modules for player economy, statistics, locations, countdowns, leaderboards, player ranks, and disguise states.

Placeholder expansion identifiers supported: `%economy_*%`, `%kds2_*%`, `%krobloxdonutsmp2_*%`, `%economylb_*%`, `%economyrank_*%`, and `%hide_*%`.

### Economy & Player Placeholders (`%economy_*%` / `%kds2_*%` / `%krobloxdonutsmp2_*%`)

| Placeholder | Description | Example Output |
| --- | --- | --- |
| `%economy_money%` | Raw money balance | `12500.50` |
| `%economy_money_formatted%` | Formatted money with currency symbol | `$12,500.50` |
| `%economy_money_short%` / `%economy_nicestMoney%` | Compact formatted money amount | `12.5k` |
| `%economy_money_short_formatted%` | Formatted compact money with symbol | `$12.5k` |
| `%economy_shards%` | Raw shards balance | `500` |
| `%economy_shards_formatted%` | Formatted shards balance | `500 Shards` |
| `%economy_shards_short%` / `%economy_nicestShards%` | Compact formatted shards amount | `1.2k` |
| `%economy_shards_short_formatted%` | Formatted compact shards with symbol | `1.2k Shards` |
| `%economy_kills%` | Total player kill count | `42` |
| `%economy_deaths%` | Total player death count | `10` |
| `%economy_killstreak%` | Current active killstreak | `5` |
| `%economy_highestkillstreak%` | Highest recorded killstreak | `12` |
| `%economy_playtime%` | Total formatted playtime duration | `3d 14h 22m` |
| `%economy_blocksplaced%` | Total blocks placed count | `15400` |
| `%economy_blocksbroken%` | Total blocks broken count | `48200` |
| `%economy_mobskilled%` | Total mob kills count | `1280` |
| `%economy_moneyspent%` | Total money spent in shop/marketplaces | `50000.00` |
| `%economy_moneymade%` | Total money earned from selling/markets | `120000.00` |
| `%economy_team%` | Player's team name | `TITANS` or `none` |
| `%economy_username%` | Public display username (respects `/hide` disguise) | `Steve` |
| `%economy_ping%` | Player ping latency in ms | `24` |
| `%economy_x%` / `%economy_coord_x%` | Player X coordinate (respects coordinate obfuscation) | `120` |
| `%economy_y%` / `%economy_coord_y%` | Player Y coordinate (respects coordinate obfuscation) | `64` |
| `%economy_z%` / `%economy_coord_z%` | Player Z coordinate (respects coordinate obfuscation) | `-350` |
| `%economy_coords%` / `%economy_location%` | Formatted X, Y, Z coordinates string | `120, 64, -350` |
| `%economy_randomized_coords%` | Returns `true`/`false` if coordinate obfuscation is active | `false` |
| `%economy_donutplus%` | Displays Donut+ badge if player has permission | `&d&lDonut+ &r` |
| `%economy_keyall_countdown%` | Formatted countdown until automatic key-all reward | `05:32` |
| `%economy_booster_countdown%` | Formatted countdown for active shard booster | `14:20` or `inactive` |
| `%economy_rtp_countdown%` | Formatted countdown for RTP zone cooldown | `00:45` or `disabled` |
| `%economy_billford_countdown%` | Formatted countdown for Billford rotation | `02:15:00` or `disabled` |
| `%economy_shard_cuboid_display%` | Shard cuboid display status indicator | `[Inside Zone]` |
| `%economy_shard_cuboid_status%` | Shard cuboid status | `inside` or `outside` |
| `%economy_shard_cuboid_name%` | Name of active shard cuboid region | `MainShardArea` or `none` |
| `%economy_money_symbol%` | Currency symbol for money | `$` |
| `%economy_money_symbol_colored%` | Colored currency symbol for money | `&$` |
| `%economy_shards_symbol%` | Currency symbol for shards | `⬟` |
| `%economy_shards_symbol_colored%` | Colored currency symbol for shards | `&d⬟` |

### Leaderboard Placeholders (`%economylb_*%` / `%economy_top_*%`)

Syntax: `%economylb_<type>_<position>_<property>%` or `%economy_top_<type>_<position>_<property>%`

- **Leaderboard Types (`<type>`)**: `money`, `shards`, `kills`, `deaths`, `killstreak`, `highestkillstreak`, `playtime`, `blocksplaced`, `blocksbroken`, `mobskilled`, `moneyspent`, `moneymade`
- **Positions (`<position>`)**: Rank index starting from `1` (e.g. `1`, `2`, `3`, `10`)
- **Properties (`<property>`)**:
  - `name`: Username of the player at position
  - `value`: Full un-truncated value of the player at position
  - `value_short` / `short`: Compact formatted value (e.g. `15.4M`)
  - `rank`: Rank number index
  - `display`: Pre-formatted entry line e.g. `#1 Notch: $15.4M`

Examples:

```
%economylb_money_1_name%       -> Notch
%economylb_money_1_value%      -> $15,400,000.00
%economylb_money_1_value_short% -> 15.4M
%economylb_kills_3_display%     -> #3 Alex: 450
%economy_top_shards_1_name%    -> EnderKing
```

### Rank Leaderboard Placeholders (`%economyrank_*%`)

Syntax: `%economyrank_<type>%`

Returns the player's personal rank position number on the specified leaderboard type (e.g. `1`, `15`, or `0` if unranked).

Examples:
- `%economyrank_money%` -> `5`
- `%economyrank_kills%` -> `1`

### Hide & Disguise Placeholders (`%hide_*%`)

Syntax: `%hide_<property>%`

| Placeholder | Description | Example Output |
| --- | --- | --- |
| `%hide_active%` | Returns `true` or `false` if player has an active disguise or alias | `true` |
| `%hide_name%` / `%hide_public_name%` | Player's formatted public display name | `ShadowNinja` |
| `%hide_plain_name%` | Player's plain unformatted public display name | `ShadowNinja` |
| `%hide_mode%` | Active disguise mode (`NONE`, `SCRAMBLE`, `ALIAS`, `DISGUISE`) | `ALIAS` |
| `%hide_alias%` | Active custom alias string | `ShadowNinja` |
| `%hide_skin%` | Active custom skin username | `CustomSkin123` |

## License and Terms

KrobloxDonutSmp2 is free, proprietary software.

- The plugin is free to use but remains under a proprietary license.
- Redistribution, resale, sublicensing, public mirroring, or unauthorized sharing is not permitted without written permission.
- You may modify the source for use on your own server; modified builds may not be distributed.
- The shaded jar bundles third-party libraries under their own licenses (Apache 2.0, MIT, and GPLv2 with the Universal FOSS Exception).
- For full licensing terms, see [LICENSE.md](LICENSE.md).
- For contribution guidelines and rules, see [CONTRIBUTING.md](CONTRIBUTING.md).

Copyright (c) 2026 KrobloxDonutSmp2. All rights reserved.

## Support

| Channel | Use it for |
| --- | --- |
| [GitHub Issues](https://github.com/KrobloxDev/KrobloxDonutSmp2/issues) | Bug reports, feature requests, and documentation problems |
| [Discord](https://discord.gg/BVjH4yqfFd) | Setup help, configuration questions, and general discussion |
| [`docs/wiki/`](docs/wiki) | Guides, configuration reference, and the FAQ |

When reporting an issue, include:

- Plugin version and jar file name
- Server software and version (Paper, Purpur, Pufferfish, Spigot, or Folia)
- Java version
- Relevant configuration snippets with secrets removed
- Console errors or stack traces
- Steps to reproduce the issue

Do not share database credentials, Redis passwords, Discord webhook URLs, or other sensitive server data in public channels.
