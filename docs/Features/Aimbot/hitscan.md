# Hitscan

The hitscan aimbot options dictate how the aimbot will work on weapons which are [hitscan](https://en.wikipedia.org/wiki/Hitscan).

## Options

### Sort method

The sort method chooses how it prioritizes which player to aim at. FOV means it will choose whoever has the least amount of distance from the center of your crosshair, while distance means it will choose whoever has the least amount of in-game distance from your players position.

There are 3 aim methods for hitscan aimbot:

1. Plain - Plain aimbot will snap your camera to where it aims at instantly.
2. Smooth - Smooth aimbot will snap your camera to where it should aim slowly, making it appear more "legit" in some cases.
3. Silent - Silent aimbot will aim at the target, but your camera doesn't look at them.

### Tapfire

Tapfire is a method of maintaining first shot accuracy on weapons affected by spread, like the minigun, pistol or revolver. If it's set to be on the distance option it will only tapfire above 1000 units of distance to the enemy, but if it's set to always it will tapfire regardless of distance.

### Smooth factor

Smooth factor affects how long it takes for the aimbot to reach its target. Higher is smoother, lower is snappier.

### Scan hitboxes

Scan hitboxes is a drop down of what bones on an enemy the aimbot will try to aim at. I believe this aims at whichever bone is closest to your crosshair.

### Multipoint hitboxes

Multipoint hitboxes attempts to aim at multiple different points on a hitbox, enabling this can cause inaccuracy at high point scale.

### Point scale

Point scale dictates how much the mins and maxs of each hitbox is scaled by.

### Buildings multipoint

Buildings multipoint will enable multipoint aimbot on buildings.

### Wait for headshot

Wait for headshot will delay the aimbot when scoping in / using the ambassador to not shoot unless you would be able to headshot because there is a slight delay when scoping in before you can actually headshot.

### Wait for charge

Wait for charge will wait for your sniper rifle to be charged to be able to kill the target in 1 shot. If fully charged it will shoot regardless of if it kills or not.

### Smooth if spectated

Smooth if spectated will force your aimbot to be smooth if you're being spectated by a teammate. 

### Scoped only

Scoped only will make the aimbot only run as sniper if you are scoped in.

### Auto scope

Auto scope will automatically scope in for you when going to shoot.

### Auto rev minigun

Auto rev minigun will rev the minigun when the aim key is held.

### Bodyaim if lethal

Bodyaim if lethal will shoot the body hitbox if it would kill them in 1 shot or you have enough sniper charge to kill in one shot.
