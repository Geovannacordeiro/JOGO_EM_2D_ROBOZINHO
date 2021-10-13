# Physics Platformer

This demo uses [`RigidBody2D`](https://docs.godotengine.org/en/latest/classes/class_rigidbody2d.html)
for the player and enemies.
These character controllers are more powerful than
[`KinematicBody2D`](https://docs.godotengine.org/en/latest/classes/class_kinematicbody2d.html),
but can be more difficult to handle, as they require
manual modification of the RigidBody velocity.

Language: GDScript

Renderer: GLES 3 (particles are not available in GLES 2)

Check out this demo on the asset library: https://godotengine.org/asset-library/asset/119

## Como funciona??

O jogador e os inimigos usam caráter dinâmico
controladores de movimento, feitos com
[`RigidBody2D`](https://docs.godotengine.org/en/latest/classes/class_rigidbody2d.html),
o que significa que eles podem interagir perfeitamente com a física
(há uma gangorra e você pode até montar em inimigos).
Por causa disso, todo movimento deve ser feito em sincronia com
o motor de física, dentro de `_integrate_forces()`.

## Screenshots

![Screenshot of the beginning](screenshots/beginning.png)

![Screenshot of the seesaw and the player riding an enemy](screenshots/seesaw-riding.png)

## Music

"Pompy" by Hubert Lamontagne (madbr) https://soundcloud.com/madbr/pompy
