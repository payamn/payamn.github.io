---
layout:     project
title:     Relational Graph Learning for Crowd Navigation
date:       2020-08-01
code: https://github.com/ChanganVR/RelationalGraphLearning
doc: https://arxiv.org/pdf/1909.13165.pdf
demo: U3quW30Eu3A
best:       true
image_small: /files/projects_files/2020-10-01-Relational-Graph-Learning-for-Crowd-Navigation.png
short:  "Designed a relational graph learning approach for robotic crowd navigation using model-based deep reinforcement learning that plans actions by looking into the future. Tools: Pytorch, ROS, Stage, Python, OpenCV"

---
We present a relational graph learning approach for robotic crowd navigation using model-based deep reinforcement learning that plans actions by looking into the future. Our approach reasons about the relations between all agents based on their latent features and uses a Graph Convolutional Network to encode higher-order interactions in each agent’s state representation, which is subsequently leveraged for state prediction and value estimation. The ability to predict human motion allows us to perform multi-step lookahead planning, taking into account the temporal evolution of human crowds. We evaluate our approach against a state-of-the-art baseline for crowd navigation and ablations of our model to demonstrate that navigation with our approach is more efficient, results in fewer collisions, and avoids failure cases involving oscillatory and freezing behaviors.
