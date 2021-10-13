# Jogo 2D


Languagem: GDScript

## Como funciona??

O jogador e os inimigos usam caráter dinâmico
controladores de movimento, feitos com
[`RigidBody2D`](https://docs.godotengine.org/en/latest/classes/class_rigidbody2d.html),
o que significa que eles podem interagir perfeitamente com a física
(há uma gangorra e você pode até montar em inimigos).
Por causa disso, todo movimento deve ser feito em sincronia com
o motor de física, dentro de `_integrate_forces()`.

## Imagens

![Screenshot of the beginning](screenshots/beginning.png)

![Screenshot of the seesaw and the player riding an enemy](screenshots/seesaw-riding.png)

## Imagens dentro do Aplicativo

<img width="769" alt="imagens do jogo Códigos" src="https://user-images.githubusercontent.com/89104769/137215985-e5d6ec78-c5f7-4be4-8c2f-a98b6433a9c9.png">

<br>

<img width="743" alt="imagens do jogo" src="https://user-images.githubusercontent.com/89104769/137216103-db7c3021-abac-4b62-83c7-b748e2500a05.png">




