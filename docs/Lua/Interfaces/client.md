# Client

## Methods

### `ChatPrintf(msg)`

Print the given message in the chat without sending it to other players.

## Examples

```lua title="Prints 'Hello, World!' in the chat"
local Client = Interfaces.GetClient()

Client:ChatPrintf("Hello, World!")
```
