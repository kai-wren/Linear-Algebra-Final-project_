# Linear Algebra Final Project
Authors: Olexiy Nagirny, Natalia Novosad

Training of REINFORCE and Advantage Actor-Critic algorithms on LunarLander environment.




Note: In PyTorch codebook we decided to not concentrate on the "from-the-scratch" implementation of Adam optimizer since we don't compare optimizers in our RL policy gradient analysis, given that Adam is generally decided to be the best option nowadays on complex environments. But if you still want to see 'from the scratch implementation' we decided to create a separate training book for simpler CartPole environment where our optimizer is implemented from scratch.

Huge credit goes to Maxim Lapan's "Deep Reinforcement Learning Hands-On" book as we base our code on his examples:
https://github.com/PacktPublishing/Deep-Reinforcement-Learning-Hands-On
