# Infinity of Spades - svg fractal playing cards.

The fractals on these cards are generated primarily using [iterated function systems](https://en.wikipedia.org/wiki/Iterated_function_system).
The idea is simple:
Figure out a set of transformations to apply to copies of the base image (a card pip), 
then apply those same transformations to the entire set of copies, 
and iterate as desired.

This method of rendering fractals is simple in execution but is very innefficient when it comes to rendering. 
It may take very large amounts of memory, and quite some time to view these fractals at higher iteration depths.

The images in this repo use the public domain suit icons from the [Singularity Deck, by Matthew Ross](https://www.singularity.games/p/deck.html).

[Credit to Stefan Goessner for the idea.](https://goessner.net/articles/svg/fractals/)
