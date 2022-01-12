# A.I learns to play Atari's Breakout (Reinforcement Learning)-
Using the "Advantage Actor Critic(A2C)" Reinforcement Learning method, the A.I is trained to play Atari's Breakout.

## The Game:

The game used for this Model is Atari's Breakout

![breakoutGame](/pics/10.png)

The game was used by downloading ROM files.

[AtariMania 'ROMS'](http://www.atarimania.com/roms/Roms.rar)

![importingbreakoutGame](/pics/7.png)

## The Algorithm:

The A2C algortihm has been implemented for the Agent to play the game

refer the paper: 

[Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/pdf/1602.01783.pdf)

## Models:

- Mark I(100k TimeSteps): 

The first Model is a Preliminary Model which has been trained with 100k TimeSteps.

![100k](/pics/6.png)

#### Highest Score:

![100KScore](/pics/8.png)

- Mark II(2M TimeSteps):

The Second model is an improved model that has been trained for 2 Million TimeSteps. The Performance was significantly better

![2M](/pics/2.png)

#### Highest Score:

![2MScore](/pics/9.png)

## Tensorboard:

These show as to how the Model kept getting better and better, where the Agent was able to score higher.

![2MScore](/pics/3.png)

![2MScore](/pics/4.png)

![2MScore](/pics/5.png)

## Better Performance:

The Agent was able to score way better with the 2M TimeSteps trained Model while Testing.

![2MScore](/pics/10.png)

![2MScore](/pics/11.png)

![2MScore](/pics/1.png)

If the Model were to be trained for longer TimeSteps, it would perform more effectively. 

Have Fun

Yours Truely,
Anuraag Rath :P
