---
title: "Literals, variables and constants"
---

## Literals
A literal is a directly defined value. ``"25"`` is a literal. So is `true`

In Python, this is an example of a literal:

```py
print(5 + 3) 
```

Both 5 and 3 are literals in this context, because they are definied exactly where they are used.

![[sixth/Computer Science/Programming/img/Pasted image 20220908115725.png]]

## Variables
A variable is an object with an assigned value that can be referenced elsewhere in the program. It is useful for dynamically updating a value.

`bobAge = 50` is a variable.

![[sixth/Computer Science/Programming/img/Pasted image 20220908115815.png]]

Naming conventions should be followed when naming variables to prevent misunderstandings.

If your variable is called `penisland` there may be issues with people not reading Pen Island.

So naming a variable `pen_island` would be better. This is what PEP8 recommends, and is therefore the best option for naming variables in Python (if you want people to like you).

Conventional naming would be `penIsland` though. Camelcase means the first word of a variable is lowercase and then all additional words in the name should start with a capital.

## Constants
A constant is a variable that CANNOT be changed after definition. The idea of a constant is to define a reused value once at one point in the code, and then allow for it to be used everywhere. if you want to change the speed of the player in your game, you can change the constant at first definition, avoiding a huge amount of refactoring.
Python does not actually support constants, but a normal variable can be treated like a constant with:

`SPEED = 5.0`

![[sixth/Computer Science/Programming/img/Pasted image 20220908115902.png]]

[Go home](/)
