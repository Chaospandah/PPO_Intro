# PPO Intro for Continous Robotic Arm Control

## Overview

This is my first reinforcement learning project that trains a simulated robotic arm using PPO.

The project uses the MuJoCo Reacher-v5 environment, where a two-joint robotic arm must move its fingertip toward a target. A random-action policy is evaluated first to establish a baseline. PPO is then trained and evaluated under the same starting conditions.

The goal with this mini project was for me to learn the practical RL workflow:

Observation → Action → Environment step → Reward → Policy update
