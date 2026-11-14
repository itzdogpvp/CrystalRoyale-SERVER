# Haven MC

**Minecraft Crystal PvP battle royale** · `HavenMC.net`

Drop into the arena, loot chests, and fight to be the last player standing. This repository tracks Haven MC server updates and player-facing changes.

## How to play

1. **Join the lobby.** When a host opens a match, players on the server are queued as space allows.
2. **Drop into the arena.** You start with enchanted gold gear, eight golden apples, totems, pearls, crystals, and anchor supplies.
3. **Loot and fight.** Use the Chest Radar to find Common, Rare, and Legendary chests. Chests refill and can change rarity during the match.
4. **Survive.** The match scoreboard shows elapsed time, the next refill countdown, and players alive. If eliminated, spectate or return to the lobby with `/leave`.

## Loot and abilities

| Item | What it does |
| --- | --- |
| Armor Upgrade | Upgrades your armor, sword, and pickaxe from gold through netherite. The final tier adds a second Blast Protection piece. |
| Ender Pearl Disabler | Hit a player with it to lock their ender pearls for 16 seconds. |
| Speed Boost | Grants Speed II for 16 seconds. |
| Launcher | Launches you into the air. |

## Progression

Kills and wins earn Royale XP and coins. Higher finishes can earn extra coins. Your Minecraft XP bar shows your Royale level and progress toward the next one.

| Command | What it does |
| --- | --- |
| `/stats` | Opens your profile with total kills, wins, level, and XP progress. |
| `/stats <player>` | Opens another player's profile, including offline players who have joined before. |
| `/leave` | Returns you to the lobby from a match or spectator mode. |

## Server changes

- **Lobby.** The global spawn is the return point for every arena. Lobby nametags display rank, username, wins, and level. Match players switch back to standard TAB nametags.
- **Scoreboards.** The Haven MC lobby sidebar shows the player's profile and lifetime stats. The arena sidebar shows live match information.
- **Loot balance.** Golden apples can drop from chests. Common and Rare chests have a 30% and 45% chance, respectively, to roll a Pearl Disabler, Speed Boost, or Launcher.
- **Combat.** Fixed a respawn-anchor error that could interrupt kill attribution.

## Reporting issues

Open a GitHub issue with what happened, what you expected, and the arena or match phase. Include a screenshot or clip if it shows the problem.
