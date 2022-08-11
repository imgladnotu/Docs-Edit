# BaseEntity

Can be a player, NPC, or any other entity.

---

## Constructor

### `BaseEntity(entityPointer)`

Creates a entity object from a pointer. You can use this when looping through a list of entity pointers.

---

## Methods

### `IsValid()`

If the entity is valid. Returns a bool. This runs before every other function.

### `GetIndex()`

Returns the index of the entity as a number.

### `GetOrigin()`

Returns the origin location of the entity as a Vec3.

### `GetAngles()`

Returns the absolute angles of the entity as a Vec3.

### `GetEyeAngles()`

Returns the eye angles of the entity as a Vec3.

### `GetClassID()`

Returns the class ID of the entity as a number.

### `GetClass()`

Returns the class name of the entity as a string.

### `GetHealth()`

Returns the health of the entity as a number.

### `GetAmmo()`

Returns the ammo of the entity as a number.

### `GetFlags()`

Returns the flags of the entity as a number.

### `GetEyePos()`

Returns the eye position of the entity as a Vec3.

### `IsDormant()`

If the entity is dormant. Returns a bool.

### `IsAlive()`

If the entity is alive. Returns a bool.

### `GetTeam()`

Returns the team of the entity as a number.

### `SetOrigin(origin)`

Sets the origin of the entity.

### `SetAngles(angles)`

Sets the angles of the entity.

### `SetEyeAngles(angles)`

Sets the eye angles of the entity.
