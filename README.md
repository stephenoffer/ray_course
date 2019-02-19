# Distributed AI with the Ray Framework Course

## Summary

Learn how to build large-scale AI applications using Ray, a high-performance distributed execution framework from the RISELab at UC Berkeley. Simplify complex parallel systems with this easy-to-use Python* framework that comes with machine learning libraries to speed up AI applications.

This course provides you with practical knowledge of the following skills:

- Use remote functions, actors, and more with the Ray framework

- Quickly find the optimal variables for AI training with Ray Tune

- Distribute reinforcement learning algorithms across a cluster with Ray RLlib

- Deploy AI applications on large computer clusters and cloud resources

The course is structured around eight weeks of lectures and exercises. Each week requires approximately two hours to complete.

### Acknowledgements

Ray official [repository](https://github.com/ray-project/ray).

Course material compiled from Ray tutorial (repo)[https://github.com/ray-project/tutorial].

## [Week 1](week_1)

Get an introduction to the Ray framework and data parallelism. Topics include how to:

- Run tasks in parallel using remote functions

- Make dependencies between remote tasks through object IDs

- Create nested tasks and remote functions within remote functions



## [Week 2](week_2)

Learn about Ray actors, which are remote functions that have states. Additional topics:

- How to implement Ray actors using Python* classes

- How to use different hardware resources for various AI tasks, such as training and inference

- The analytics ecosystem, which is made up of toolkits, libraries, solutions, and hardware


## [Week 3](week_3)

Understand how to optimize and speed up functions. Topics include how to:

- Avoid waiting for slow tasks using ray.wait()

- Process remote tasks in a specific order

- Speed up serialization by passing objects to ray.put()

## [Week 4](week_4)

Explore how to optimize functions, including:

- Accelerate Pandas* workflows by changing one line of code

- Implement a MapReduce system with Ray

- Use Tree Reduce to execute a tree of dependent function in parallel

## [Week 5](week_5)

Learn to access different hardware resources, including how to:

- Send remote tasks to different accelerators and processors

- Use custom resources for tasks that require complex hardware combinations

## [Week 6](week_6)

Get an introduction to training neural networks across multiple workers. Topics include:

- An example of how to pass the weights of a TensorFlow* model between workers and drivers

- How to implement a sharded parameter server for distributing parameters across multiple workers

## [Week 7](week_7)

Understand how to use Ray Tune, a scalable framework for searching for hyperparameters.

- Use Tune to reduce one of the most expensive parts of machine learning

- Search for the right parameters, such as learning rate and momentum, to train a neural network

- Combine HyperOpt and HyperBand to perform a more powerful search

## [Week 8](week_8)

Learn about RLlib, which is a scalable reinforcement learning library to train AI agents.

- Get an introduction to the Markov Decision Process and how to use it in Python*

- See an example of how to use the PPO algorithm to train a network to play a simple game with Gym* and visualize the results with TensorBoard*

- Learn to create a deep-Q network (DQN) to play Pong and play against it in a browser
