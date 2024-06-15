# Variables
**All Level and XP Variables get set on-join**


## Eco and Multi Variables

### Economy

- {stars::%player's uuid%} - the amount of stars a player has
- player's balance - the amount of money a player has

### Multipliers
- {multiplier.fishing::%player's uuid%} - the multiplier put on the /sellfish command
- {multiplier.tradeshop::%player's uuid%}
- {multiplier.}

## Stat Variables

### XP and Level Variables

-


## "Secret" Variables

### Player Variables

- {secret.found.%number%::%player's uuid%} - true if the player has found that secret
- {secret.found.total::%player's uuid%} - represents the total number of secrets that player has found
- {secret.found.%area%::%player's uuid%} - represents the total number of secrets that player has found in that area
- {secret.found.all::%player's uuid%} - true if the player has found every secret
- {secret.found.all.%area%::%player's uuid%} - true if the player has found all of the secrets in that area

- {secret.item.purchased.%item_name%::%player's uuid%} - true if the player has purchased that secret item

### Location Variables

- {secret.location.%number%} - location of the secret
-



## Admin Variables


### Player Variables

- {admin.warnings::%player's uuid%} - the amount of warnings that player has - **DEFAULTED TO 0**



## Area Variables


### Player Variables

- {area.teleport_cooldown::%player's uuid%} returns true if the player has a cooldown on using an area teleport


### Location Variables

- {area.%area%.enterance_block} - location of the block that teleports the player into that area (from the previous area)
- {area.%area%.enterance_teleport} - the location you get teleported to when entering an area (from the previous area)
- {area.%area%.exit_block} - location of the block that teleports the player out of that area (into the previous area)
- {area.%area%.exit_teleport} - the location you get teleported to when exiting an area (into the previous area)
