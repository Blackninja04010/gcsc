# Dev logs

## Dev Logs 1
Date: 6/14/24-

### General

- [x] Moved `sell.sk` into `fishing.sk`
- [x] Moved the `/spawn` command into `commands.sk`
- [x] Moved the *kills*, *deaths*, *kill streak*, and *kill ratio* from `stats.sk` to `combat.sk`
- [x] Moved the *fishing* section from `stats.sk` to `fishing.sk`
- [x] Moved the *tradeshop*, *fishing*, *crate* multiplier variables to `stats.sk`

- [x] Revamped `areas.sk`, also now (temporarily) called `areas-2.sk`
- [x] Revamped `secrets.sk`, also now (temporarily) called `secrets-2.sk`
- [x] Revamped `combat.sk`, also added `combatlog.sk` to `combat.sk`
- [ ] Revamped `shopgui.sk`
- [ ] Revamped `crates.sk` and added the mythical crate
- [ ] Revamped `levels.sk` and added a refresh function

- [x] Deleted obsolete files

- [x] `combat.sk` updated with the new vars
- [x] `scoreboard.sk` updated with the new vars
- [x] `shopgui.sk` updated with the new vars
- [x] **Variable reset**

- temporarily disabled the levelup menu due to me not being able to get the revamped version to work (*yet*)

### Plugin

- Updated Skript from 2.8.5 to 2.8.6
- Updated PlaceHolderAPI from 2.11.5 to 2.11.6
- Updated SkBee from 3.5.0 to 3.5.3
- Updated WorldEdit from 7.2.14 to 7.3.3

### Var changes
- Variable changes:

{rank.secrets_p::%player's uuid%} > {rank.secret-prefix::%player's uuid%}
{rank.secrets_s::%player's uuid%} > {rank.secret-suffix::%player's uuid%}

{area.perm::%player's uuid%::number} > {area.perm::%player's uuid%}
{forest.entry.purchased::%player's uuid%} > {area.forest.purchased::%player's uuid%}

{fishing.multi::%player's uuid%} > {multiplier.fishing::%player's uuid%}
{trade.multi::%player's uuid%} > {multiplier.tradeshop::%player's uuid%}

{Stats.tradeshop.xp::%player's uuid%} > {stat.xp.tradeshop::%player's uuid%}
{Level.tradeshop::%player's uuid%} > {stat.level.tradeshop::%player's uuid%}
{Stats.kill.xp::%player's uuid%} > {stat.xp.kills::%player's uuid%}
{Level.kills::%player's uuid%} > {stat.level.kills::%player's uuid%}
{Stats.playtime.xp::%player's uuid%} > {stat.xp.playtime::%player's uuid%}
{Level.playtime::%player's uuid%} > {stat.level.playtime::%player's uuid%}
{bounty.level::%player's uuid%} > {stat.level.bounty::%player's uuid%}

{Stats.killratio::%player's uuid%} > {stat.kill_ratio::%player's uuid%}
{Stats.kills.skeleton::%player's uuid%} > {stat.kills.skeleton::%player's uuid%}
{Stats.kills.zombie::%player's uuid%} > {stat.kills.zombie::%player's uuid%}
{Stats.kills.pve::%player's uuid%} > {stat.kills.pve::%player's uuid%}
{Stats.kills::%player's uuid%} > {stat.kills::%player's uuid%}
{Stats.deaths::%player's uuid%} > {stat.deaths::%player's uuid%}
{Stats.fishcaught::%player's uuid%} > {stat.fish_caught::%player's uuid%}
{Stats.chat-event.won::%player's uuid%} > {stat.chat-event.won::%player's uuid%}

{Stats.online::%player's uuid%} > {stat.online::%player's uuid%}

{crate.key.xxxx::%player's uuid%} > {}

- New/deleted Variables

+ {stat.fish_missed::%player's uuid%}
