# Engine

Engine is the main class of the engine. It is responsible for managing the game loop, the game state, the game objects, the game input, the game audio, the game graphics, and the game physics.

## Methods

### `IsInGame()`

If the player is in a game. Returns a bool.

### `IsConnected()`

If the player is connected to the server. Returns a bool.

### `IsTakingScreenshot()`

If the player is taking a screenshot. Returns a bool.

### `ExecuteCommand(command)`

Execute a command without restrictions.

### `GetLocalPlayer()`

Returns the local player.

### `GetMaxClients()`

Returns the maximum amount of players.

### `GetLevelName()`

Returns the name of the current map.

### `GetScreenSize()`

Returns the screen size as a Vec3.

### `GetViewAngles()`

Returns the view angles as a Vec3.

### `SetViewAngles(angles)`

Sets the view angles.

### `GetPlayerForUserID(userID)`

Returns an entity index from a user ID.

## Examples

``` lua title="Print the current view angles"
local Engine = Interfaces.GetEngine()
local viewAngles = Engine:GetViewAngles()

print("Viewangles: " .. viewAngles.x .. " " .. viewAngles.y .. " " .. viewAngles.z)
```
