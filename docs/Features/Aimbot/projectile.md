# Projectile

Projectile aimbot will attempt to predict where players are going to be and aim at that predicted area. It is impossible for projectile aimbot to not miss.

---

Prediction time is an important factor if you are on a slow PC. It is an upper limit for how long it will try to predict a players movement for.

The sort method chooses how it prioritizes which player to aim at. FOV means it will choose whoever has the least amount of distance from the center of your crosshair, while distance means it will choose whoever has the least amount of in-game distance from your players position.

There are 2 aim methods for hitscan aimbot:

- **Plain** - Plain aimbot will snap your camera to where it aims at instantly.
- **Silent** - Silent aimbot will aim at the target, but your camera doesn't look at them.

Smooth is not worth implementing for projectile aimbot as it is pSilent, which means it's invisible to spectators and demo recordings.

Priority hitbox lets you choose what area of the players body to always aim at if available. Auto will choose a suitable option based on the weapon you're using (i.e. head for huntsman sniper)

Allowed hitboxes controls what hitboxes the aimbot is allowed to even consider shooting at.

Point VisTest limit controls how many points on the player the cheat will test a shot at.

Point scan limit is limited by point VisTest limit, and controls how many visible points it needs to find before it picks one to aim at.

Point scale controls the size of the hitbox as it's given to the cheat.

Feet aim on ground will override your priority hitbox/allowed hitboxes and force you to aim at their feet if the player is on the ground (not in the air). 
