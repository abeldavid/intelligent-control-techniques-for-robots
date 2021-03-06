# Intelligent Control Techniques for Robot Manipulators.
**An analysis of different intelligent control techniques (evolutionary alg., reinf. learn., neural networks) applied to robot manipulator.**

Here you can find the blogposts describing this work: https://medium.com/towards-data-science/making-a-robot-learn-of-to-move-intro-2bcf3c3330df.

**WORK IN PROGRESS**

Work by **Norman Di Palo** and **Tiziano Guadagnino**.

We explore the performance of different AI/Machine Learning techniques applied to trajectory tracking for a 3R robotic manipulator, whose dynamical model is unknown. Thus, the robot needs to learn of to precisely follow a trajectory to decrease the position and velocity error.
Our baseline is a classic PD controller.

You can find the code for **Evolutionary Algorithms** applied to neural network controllers and **reinforcement learning** techniques such as **Q-learning for Dynamic PD Tuning** and **Actor Critic for deterministic policy learning**, and then **Inverse Dynamic Model Learning by Feedback-Backpropagation**.
