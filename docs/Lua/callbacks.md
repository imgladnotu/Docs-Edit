# Callbacks

Callbacks allow you to hook into some of the games functions and run your code.

## Callbacks

### `CreateMove(UserCmd)`

Called every time an user update is going to be sent to the server.
You can use this to modify movement and do all kind of interactive stuff.

### `Draw()`

Called everytime the game starts drawing.
You can use this to draw your own shapes on the screen.

### `FireGameEvent(GameEvent)`

Called every time the game receives an event from the server.
You can use this to do specific things when anything in the game happens (Player deaths, Damage, etc.)

### `DispatchUserMessage(UserMessage)`

Called every time the game receives a user message from the server.
This can be chat messages, voic menu interactions etc.

### `FrameStageNotify(ClientFrameStage)`

Called when starting, rendering and ending a frame. The current stage of the frame is passed as a parameter.

## Usage

### `Register(type, name, callback)`

Registers a callback for the given type and name.

### `Unregister(type, name)`

Unregisters the given callback.

## Examples

``` lua title="Print the forward movement"
function OnCreateMove(userCmd)
    print("Forward movement: " .. userCmd:GetForwardMove())
end

Callbacks.Unregister("CreateMove", "Example_CreateMove")
Callbacks.Register("CreateMove", "Example_CreateMove", OnCreateMove)
```
