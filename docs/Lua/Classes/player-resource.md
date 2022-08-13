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

### `GetTeam(index)`

Returns the team of the player with the given index.

### `IsAlive(index)`

Returns if the player with the given index is alive.

### `GetHealth(index)`

Returns the health of the player with the given index.

### `GetAccountID(index)`

Returns the account ID (SteamID 3) of the player with the given index.

### `GetValid(index)`

Returns the valid status of the player with the given index.

### `GetPlayerName(index)`

Returns the name of the player with the given index.

### `GetScore(index)`

Returns the score of the player with the given index.

### `GetDamage(index)`

Returns the damage of the player with the given index.

### `GetMaxHealth(index)`

Returns the max health of the player with the given index.

## Examples

``` lua title="Print the ping of the local player"
local localPlayer = Entities.GetLocalPlayer()
local index = localPlayer:GetIndex()

local playerResource = Entities.GetPlayerResource()
print("Ping: " .. playerResource:GetPing(index))
```
