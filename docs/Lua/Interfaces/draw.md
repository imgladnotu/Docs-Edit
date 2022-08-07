# Draw

Provides various drawing functions. Can only be used inside the `Draw` callback.

## Methods

### `Text(x, y, text)`

Draws a text on the screen.

### `Line(x, y, x1, y1)`

Draws a line on the screen.

### `Rect(x, y, w, h)`

Draws a filled rectangle on the screen.

### `OutlinedRect(x, y, w, h)`

Draws an outlined rectangle on the screen.

### `FilledCircle(x, y, radius)`

Draws a filled circle on the screen.

### `SetColor(r, g, b, a)`

Sets the current color for all upcomming drawing functions.

## Examples

```lua title="Draw shifted ticks on the screen"
local Draw = Interfaces.GetDraw()

function OnDraw()
    Draw:SetColor(255, 0, 0, 255)
    Draw:Text(40, 80, "Shifted Ticks: " .. Fedoraware.ShiftedTicks())
end

Callbacks.Unregister("Draw", "Example_Draw")
Callbacks.Register("Draw", "Example_Draw", OnDraw)
```
