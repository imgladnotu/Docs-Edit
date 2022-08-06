# PlayerResource

Contains information about the players in the game. You have to pass the index of the player.

## Methods

### `GetPing(index)`

Returns the ping of the player with the given index.

### `GetKills(index)`

Returns the kills of the player with the given index.

### `GetDeaths(index)`

Returns the deaths of the player with the given index.

### `GetConnected(index)`

Returns the connected status of the player with the given index.

### `GetValid(index)`

Returns the valid status of the player with the given index.

### `GetPlayerName(index)`

Returns the name of the player with the given index.

### `GetDamage(index)`

Returns the damage of the player with the given index.

## Examples

``` lua title="Print the ping of the local player"
local localPlayer = Entities.GetLocalPlayer()
local index = localPlayer:GetIndex()

local playerResource = Entities.GetPlayerResource()
print("Ping: " .. playerResource:GetPing(index))
```
