# RobotrekkingDRL2020
Here is the code to the paper "Visual and Dynamics Fusion on a Deep Reinforcement Learning Controlled Rover", submitted in Journal of Intelligent &amp; Robotics Systems 2020

We used the following python libraries: tensorflow and gym. Simulation was performed with mujoco


## Instaling the Environment

If $GYM is your path to the gym folder

The files inside mujoco folder must be in: `$GYM/gym/envs/mujoco`

The files inside mujoco/assets folder must be in: `$GYM/gym/envs/mujoco/assets`


And add the following lines of code in the `:$GYM/gym/envs/__init__.py` file

```python 
register(
    id='Rover4We-v1',
    entry_point='gym.envs.mujoco:RoverRobotrek4Wev1Env',
    reward_threshold=1000,
    )
```


## Demonstration

A Demonstration can be found here: 
