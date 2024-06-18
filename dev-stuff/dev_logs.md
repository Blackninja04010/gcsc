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
- [ ] Redo `crates.sk` and added the mythical crate
- [ ] Redo `levels.sk` and added a refresh function
- [ ] Redo `admin.sk`
- [ ] Redo the `/stats` command
- [ ] Redo the `/v2info` command
- [x] Redo the `/spawn` command in `commands.sk`
- [ ] Redo `charms.sk` and add a refresh function
- [ ] Redo `shop.sk` and possibly move it into `shopgui.sk`
- [ ] Fix the resource pack
- [ ] Redo `starshop.sk`, revamp, add stuff
- [ ] Redo `boss.sk`
- [ ] Redo `ranks.sk`
- [ ] Redo `events.sk`
- [ ] Redo `/warp` inside of either `commands.sk` or `areas.sk`


- [x] Deleted `blockcore.sk`
- [x] Deleted other obsolete files

- [x] `combat.sk` updated with the new vars
- [x] `scoreboard.sk` updated with the new vars
- [x] `shopgui.sk` updated with the new vars
- [x] fix the chat filter (*may not work, it's untested*)
- [x] **Variable reset**

- temporarily disabled the levelup menu due to me not being able to get the revamped version to work (*yet*)

### Plugin

- Updated Skript from 2.8.5 to 2.8.7
- Updated PlaceHolderAPI from 2.11.5 to 2.11.6
- Updated SkBee from 3.5.0 to 3.5.4
- Updated WorldEdit from 7.2.14 to 7.3.3
- Updated ViaVersion from 4.10.2 to 5.0.0
- Added ChatEvents (by meep)

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


- CHARMS
+ {charm.purchased.crit_boost::%player's uuid%} - true if player has bought that charm
{charm.purchased.Crit_Boost::%player's uuid%} > {charm.level.crit_boost::%player's uuid%}
{charms.purchased.Figher::%player's uuid%} >
{charms.purchased.Speed_Boost::%player's uuid%} >
{charms.purchased.Regen::%player's uuid%} >
{charms.cooldown.Regen::%player's uuid%} >
{charms.purchased.Undead_Damage_boost::%player's uuid%} >
{charms.purchased.Health_Boost::%player's uuid%} >
{charms.purchased.Deflection::%player's uuid%} >

- New/deleted Variables

+ {stat.fish_missed::%player's uuid%}


### Other
- Started using a Feather server to test
- Moved to coding directly on the Feather server
