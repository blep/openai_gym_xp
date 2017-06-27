# openai_gym_xp
Some simple experiment with gym.openai.com

# Installing openai gym

See https://gym.openai.com/docs for basic instruction. The following system prerequisite needs to be installed
before `pip3 install gym[all]` can succeed:

```
sudo apt-get install python3-dev
sudo apt install python3-pip
sudo apt install python3-tk
sudo apt install swig
sudo apt install cmake
sudo apt install zlib1g-dev
sudo apt-get install python3-matplotlib
```

```
sudo pip3 install gym[all]
```

# Original Google DeepMind's Deep Q-learning playing Atari Breakout paper

https://www.youtube.com/watch?v=V1eYniJ0Rnk

https://sites.google.com/a/deepmind.com/dqn/
https://github.com/kuz/DeepMind-Atari-Deep-Q-Learner
=> added visualization
http://cg.tuwien.ac.at/~zsolnai/wp/wp-content/uploads/2015/03/train_agent.patch
=> low memory configuration
http://www.cs.swarthmore.edu/~meeden/cs63/s15/nature15b.pdf
=> Nature article

# Gym environment summary

## Cartpole-v0

A reward of +1 is provided for every timestep that the pole remains upright.

CartPole-v0 defines "solving" as getting average reward of 195.0 over 100 consecutive trials. 

## Cartpole-v1

CartPole-v1 defines "solving" as getting average reward of 475.0 over 100 consecutive trials. 

## Acrobot-v1 

the goal is to swing the end of the lower link up to a given height

Acrobot-v1 is an unsolved environment, which means it does not have a specified reward threshold at which it's considered solved. 
