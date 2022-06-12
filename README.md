# Reinforcement Learning 

Experiments with the OpenAI Gym Taxi-v2 Envioe=rnment

<h> A gym environment will basically be a class with 4 functions.</h>

1. The first function is the initialization function of the class, which will take no additional parameters and initialize a class. It also sets the initial state of our    RL problem. 
2. The second function is the step function which  returns four values. 
         These are: observation (object): an environment-specific object representing your observation of the environment. For example, pixel data from a camera, joint            angles and joint velocities of a robot, or the board state in a board game.
         reward (float): amount of reward achieved by the previous action. The scale varies between environments, but the goal is always to increase your total reward.
         done (boolean): whether it’s time to reset the environment again. Most (but not all) tasks are divided up into well-defined episodes, and done being True                indicates the episode has terminated. (For example, perhaps the pole tipped too far, or you lost your last life.)
         info (dict): diagnostic information useful for debugging. It can sometimes be useful for learning (for example, it might contain the raw probabilities behind            the environment’s last state change). However, official evaluations of your agent are not allowed to use this for learning.
3. & 4. The other functions are reset, which resets the state and other variables of the environment to the start state and render, which gives out relevant information about the behaviour of our environment so far.

OpenAI Gym - https://github.com/openai/gym
