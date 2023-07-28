# Mountain Car V0
[Back to main dir](../)

* ***DQN Solution***
* ***DDPG Solution***

###DQN
___
_DQN solution for MountainCar is not the best one, but it still works._

***Here DQN model work is very unstable and changing parameters can lead to infinite training loop without result, when it catches some solution related actions bur after few iterations begins to fail again, so finetune it carefully***

First problem with this task is that reward always -1 until we solve task, so 
we should modify reward to make learning process possible

Because solution is not the best, i'm not providing pretrained DQN model, but it should achieve sume results after 50 iterations
(you could always disable render mode to make simulation quicker)


###DDPG

___
_As DDPG works only with continious action space we use continious versiopn on **MountainCar** space_

DDPG implementation is very similar to **Pendulum** task. main difference here is that without reward modification learning process will be very long and possibly unsuccessfull, because program will not know about correct way of solution (but this version still have better reward then discreet version, and here reward depends on our action value). 
Training is pretty slow because of time window of 999 steps till termination, but when program starts to achieve goal training speeds up.
As usually this program saves checkpoints of trained network.
