---
title: "Force control for robust quadrupedal locomotion: A Linear Policy approach"
collection: publications
permalink: /publication/force-control-ICRA-2023
excerpt: 'In this work, we proposed a computationally efficient control architecture consisting of a linear policy and a QP that can achieve stable and robust locomotion and handle external disturbances. We showed that our policy achieved zero-shot generalization to commanded velocities from the joystick and helped in direction-controlled walking for realworld applications'
date: 2023-05-29
venue: 'International Conference on Robotics and Automation (ICRA)'
paperurl: 'https://www.stochlab.com/papers/force_lp_ICRA_2023.pdf'
---

**Authors**: Aditya Shirwatkar\*, **Vamshi Kumar Kurva**\*, Devaraju Vinoda, Aman Singh, Aditya Sagi, Himanshu Lodha, Bhavya Giri Goswami, Shivam Sood, Ketan Nehete, Shishir Kolathaya

**Abstract**: This work presents a simple linear policy for direct force control for quadrupedal robot locomotion. The motivation
is that force control is essential for highly dynamic and agile motions. We learn a linear policy to generate end-foot trajectory
parameters and a centroidal wrench, which is then distributed among the legs based on the foot contact information using a
quadratic program (QP) to get the desired ground reaction forces. Unlike the majority of the existing works that use
complex nonlinear function approximators to represent the RL policy or model predictive control (MPC) methods with many
optimization variables in the order of hundred, our controller uses a simple linear function approximator to represent policy
along with only a twelve variable QP for the force distribution. A centroidal dynamics-based MPC method is used to generate
reference trajectory data, and then the linear policy is trained using imitation learning to minimize the deviations from the
reference trajectory. We demonstrate this compute-efficient controller on our robot Stoch3 in simulation and real-world
experiments on indoor and outdoor terrains with push recovery.

**Links**: [Paper](https://www.stochlab.com/papers/force_lp_ICRA_2023.pdf) / [Video](https://www.youtube.com/watch?v=k89QdImcqdo)
