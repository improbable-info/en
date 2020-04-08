## Cellular automata
Cellular automata show how simple rules can generate complex behavior.

We will show some examples of "Game of Life".
The rules are such that the two-dimensional grid cells can have two states - be dead or alive. Living cell in the next step is still alive, if it is next to each other 2 or 3 live cells, with a different number of neighbors die. Still a cell come to life in the next step if it is next to each other exactly 3 live neighbors. In the drawings selected living cell is black and the white cell dead.

Example 1. A simple example of evolution aimed at a state in which cells no longer a state does not change:

1a) The structures of living cells gradually disappear until the blank field:

![rysunek1a](../assets/img/obrazekA1a.jpg)

1b)  Reach to the structure, which is not changing:

![rysunek1b](../assets/img/obrazekA1b.jpg)

Example 2. Simple structure, which change periodically, and periodically return to their original state:

2a) Probably the easiest periodically changing structure:

![rysunek2a](../assets/img/obrazekA2a.jpg)

2b) I have a little more complicated structure, which changes periodically:

![rysunek2b](../assets/img/obrazekA2b.jpg)

If we have a suitable program that will show us the situations of a given number of steps, we can examine the impact may be minimal change in the initial configuration.

For example, if the initial configuration in 2b move the field a few places, then from the structure, which is repeated every few steps, it will begin an unexpected evolution:

The initial state (in the configuration of 2b shifted one field of several places):

![rysunek5a](../assets/img/obrazekA5a.jpg)

State after 71 steps:

![rysunek5b](../assets/img/obrazekA5b.jpg)

State after 80 steps:

![rysunek5c](../assets/img/obrazekA5c.jpg)

State after 409 steps:

![rysunek5d](../assets/img/obrazekA5d.jpg)

State after 730 steps:

![rysunek5f](../assets/img/obrazekA5f.jpg)

Here we can see that changing just one field may lead to a large number of new structures that can be considerably complicated and completely different from the initial structure.
