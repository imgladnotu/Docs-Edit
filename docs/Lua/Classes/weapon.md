# BaseCombatWeapon

An entity that is a weapon. Only contains weapon specific functions.
You can also extract the entity of the weapon and use it as a normal entity.

## Methods

### `IsValid()`

If the entity is valid. Returns a bool. This runs before every other function.

### `GetEntity()`

Returns the entity of the weapon as a BaseEntity.

### `GetName()`

Returns the name of the weapon as a string.

### `CanShoot()`

Returns if the weapon can shoot right now.

### `GetClip1()`

Returns the ammo of clip 1 as a number.

### `GetClip2()`

Returns the ammo of clip 2 as a number.

### `GetSlot()`

Returns the slot of the weapon as a number.

### `GetWeaponID()`

Returns the weapon ID of the weapon as a number.

### `IsInReload()`

Returns if the weapon is currently reloading.
