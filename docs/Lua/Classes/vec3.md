# Vec3

A 3-Dimensional vector consisting of `x`, `y` and `z` fields.

## Constructor

### `Vec3()`

Returns a new `Vec3` object with `x`, `y` and `z` fields set to `0`.

### `Vec3(x, y, z)`

Returns a new `Vec3` object with set `x`, `y` and `z` fields.

## Fields

### `x`

X-coordinate.

### `y`

Y-coordinate.

### `z`

Z-coordinate. Might be 0 when the Vec3 object only contains 2D data.

## Methods

### `Cross(Vec3)`

Calculates the cross product of the two vectors.

### `Dot(Vec3)`

Calculates the dot product of the two vectors.

### `DistTo(Vec3)`

Returns the distance to the given vector.

### `IsZero()`

Returns whether the vector is all zeros.

### `Length()`

Returns the length of the current vector.
