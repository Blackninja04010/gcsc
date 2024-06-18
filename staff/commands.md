# This only goes over Skript commands

## Legend
- sk.admin.1 - helper/trainee
- sk.admin.2 - jr mod
- sk.admin.3 - mod
- sk.admin.4 - sr mod
- sk.admin.5 co-owner
- sk.console owner/console
- developer - developer

- [] - required
- () - optional



### /Admin

structure: /admin <text> <text> <text> <player> <number>

commands

/admin gui - opens the admin panel (sk.admin.1)
/admin variable reset economy [player] - resets the economy variables for that player (sk.admin.3)
/admin key [add/remove/set] [common/uncommon/rare/epic/legendary/mythical] [player] [amount] - adds/removes/sets the amount of crate keys that player has for that rarity (sk.admin.3)
/admin info [reload_alerts/toggles/other] - gives information on the status of some variables (mainly used for debugging) (sk.admin.2)
/admin broadcast [kickall/restart] [confirm] [sender] [time] - broadcasts to the server that a kickall/restart will be happening in `[time]` minutes (this doesn't work if `[time]` is below 1) (sk.admin.3)
/admin [teleport/tp] [area name]
