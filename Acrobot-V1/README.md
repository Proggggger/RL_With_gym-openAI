# Acrobot V1
[Back to main dir](../)
___
### DQN
Acrobot has the same reward system as Mountain Car, but for this task we don't need to modify rewards, default one works great, in less thel 10 learning steps it starts to find working solutions. 

This notebooks contains two cells, one with a full training process, which starts from random actions and thenoptimizes task solution. After some threshold (in this case 120 iterations) for mean action time, weights for policy network are saved. ___Pay attention, training process wei overwrite existing pretrained model if it reaches threshold___

Second cell is used for testing pretrained model, so it contains simplified code without training steps, so if you already have pretrained model _(which included in this repo)_ you can run a second one
