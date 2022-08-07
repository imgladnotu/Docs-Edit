# UserMessage

Contains the data for a user message of the DispatchUserMessage callback.
You can find more information about user messages on the [Alliedmods Wiki](https://wiki.alliedmods.net/User_messages).

## Methods

### `GetType()`

Returns the type of the message as a number.

### `Reset()`

Resets the message reader.

### `Seek(bit)`

Sets the message reader to the specified bit.

### `GetDataBits()`

Returns the number of bits in the message.

### `GetNumBitsLeft()`

Returns the number of bits left in the message.

### `ReadByte()`

Reads and returns the next byte in the message as a number.

### `ReadFloat()`

Reads and returns the next float in the message as a number.

### `ReadString(length)`

Reads and returns the next string of a given length in the message as a string.
