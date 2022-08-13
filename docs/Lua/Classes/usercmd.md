# UserCmd

The UserCmd gets passed to the CreateMove callback and contains information about the current user update.

## Methods

### `IsValid()`

If the entity is valid. Returns a bool. This runs before every other function.

### `SetSendPacket(state)`

Sets whether the packet should be sent or choked. This might be overwritten by other features.

### `GetButtons()`

Returns the currently pressed movement/interaction buttons as a number.

### `GetViewAngles()`

Viewangles as Vec3.

### `GetForwardMove()`

Forward movement as number.

### `GetSideMove()`

Side strafe as number.

### `GetUpMove()`

Up/down movement as number.

### `SetButtons(buttons)`

Sets the buttons.

### `SetViewAngles(angles)`

Sets the viewangles.

### `SetForwardMove(move)`

Sets the forward movement.

### `SetSideMove(move)`

Sets the side strafe.

### `SetUpMove(move)`

Sets the up/down movement.
