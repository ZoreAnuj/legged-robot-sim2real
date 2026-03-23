# Legged Robot Sim2Real

This project adapts and extends training, simulation, and sim2real transfer code for a legged robot. It serves as a personal exploration of reinforcement learning for robotic locomotion, focusing on bridging the gap between simulated and real-world deployment.

## Key Features
*   Reinforcement learning training pipelines for legged locomotion.
*   Tools for simulation-to-simulation (sim2sim) transfer and validation.
*   Demo code for simulation-to-reality (sim2real) transfer.
*   Based on the original Sirius legged robot codebase.

## Tech Stack
*   Python
*   PyTorch
*   Isaac Gym / NVIDIA Omniverse
*   ROS 2 (for real robot integration)

## Getting Started
```bash
git clone https://github.com/zoreanuj/legged-robot-sim2real.git
cd legged-robot-sim2real
pip install -r requirements.txt
# Follow environment-specific setup for your simulator
```