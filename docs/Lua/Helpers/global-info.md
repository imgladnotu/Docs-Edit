# GlobalInfo

Global info about the game.

## Functions

### `RealTime()`

Returns the real time in seconds.

### `FrameCount()`

Returns the current frame count.

### `AbsFrameTime()`

Returns the absolute time in seconds since the game started.

### `CurTime()`

Returns the current time in seconds.

### `FrameTime()`

Time per frame.

### `MaxClients()`

Max ammount of clients.

### `TickCount()`

Returns the current tick count.

### `IntervalPerTick()`

Returns how long a tick is.

## Examples

``` lua title="Prints the current tick count"
print(GlobalInfo.TickCount())
```
