# FlappyBird
Recreated flappy bird since I lost the download on my phone. 
Give it a [play!](https://Ophirr33.github.io/FlappyBird)

Bugs:
- Compiling to javascript mashes the floor texture png and creates a strip of no-image at its top (the gray bar)
- Rotation of the bird is carried through to the menu, causing flappy bird to spin in circles while waiting for the game to start. Note that I will not fix this bug, as I find it charming (to fix it would be a one liner in the respawn method to reset rotation to 0). 
- Doesn't work on mobile devices since it's just created on Unity. Plus I don't want to make an actual mobile friendly version of Flappy Bird, too many copyright issues.
