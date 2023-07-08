# Mountain Car V0
[Back to main dir](../)
___
_DQN solution for MountainCar is not the best one, but it still works._

***Here DQN model work is very unstable and changing parameters can lead to infinite training loop without result, when it catches some solution related actions bur after few iterations begins to fail again, so finetune it carefully***

First problem with this task is that reward always -1 until we solve task, so 
we should modify reward to make learning process possible

Because solution is not the best, i'm not providing pretrained DQN model, but it should achieve sume results after 50 iterations
(you could always disable render mode to make simulation quicker)
