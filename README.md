## Flappy Bird with NEAT

## NEAT-Python
#### NeuroEvolution of Augmenting Topologies
Documentation: 
https://neat-python.readthedocs.io/en/latest/index.html

## Neat for Flappy Bird
- **Inputs**: y-position of bird, position of top pipe, position of bottom pipe
- **Outputs**: Jump
- **Activation** function: TanH
- **Population size**: 6 (Can be set to any number, but since there is only one output - the algorith can figure out what to do in just one generation, and that is not the point with this test)
- **Fitness function**: Distance
- **Max generations**: 50 (Can be set to any number, but if it hasn't managed to solve the problem by 50 generations it might be clever to try with a new set of population)

## TanH:
![TanH](https://mathworld.wolfram.com/images/interactive/TanhReal.gif)

## GIF
![flappy_neat_gif](https://github.com/andreasj0/flappy_bird_neat/blob/master/imgs/flappy_neat.gif)
