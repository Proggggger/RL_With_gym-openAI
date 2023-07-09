# Gymnasium rienforcement learning solutions
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

This repo contains some solutions of  **_Rienforcement_** learning tasks from [Gymnasium](https://gymnasium.farama.org/).
Gymnasium is a maintained fork of OpenAI’s Gym library. The Gymnasium interface is simple, pythonic, and capable of representing general RL problems.
______
All solutions are provided as an interactive [Jupyter](https://jupyter.org) notebooks to make code easy to deploy and debug. Also using a jupyter allows to run code on [google collab](https://colab.research.google.com/). Requirements file is not provided but set of packages here is pretty minimalistic and standart fo those who 
works with machine learning and AI tasks.

[Torch](https://pytorch.org) was used as a basic framework because it's easy to use and gives powerful capabilities for solving machine learning tasks. 
All solutions contains code which checks for possibility of using CUDA for computation accelerating, but mostly neural networks are small and can work even on CPU.
if you want to use CUDA accelerated version  on your local install you download cuda accelerated torch version from [official website](https://pytorch.org/get-started/locally/), because standart pip version is not accelerated.

Each environment (task) has it's own directory with it's own README file where more details about solution are provided.
___
### Currently solved tasks

#### [Classic controls](https://gymnasium.farama.org/environments/classic_control/)
All of these environments are stochastic in terms of their initial state, within a given range. In addition, Acrobot has noise applied to the taken action. Also, regarding both mountain car environments, the cars are underpowered to climb the mountain, so it takes some effort to reach the top.

* [Cart Pole](./Cart-Pole-V1)
* [Pendulum](./Pendulum-V1)
* [Mountain Car](./MountainCar-V0)
