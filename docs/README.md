# The Unified Robot Environment (URE)

## Overview:

The Unified Robot Environment (URE) is a powerful framework for training, simulating, and deploying legged robots using machine learning. Leveraging the PyBullet physics simulator, URE facilitates the development and evaluation of legged robot control algorithms. Whether you're working on research, prototyping, or educational projects, URE offers a unified environment to streamline your robot-related tasks.

## Key Features:

1. **Machine Learning Training**: URE is designed to train legged robots efficiently. It currently implements the Deep Deterministic Policy Gradient (DDPG) algorithm and the Augmented Random Search (ARS) algorithm, two powerful reinforcement learning methods.

2. **Compatibility**: URE is built to work with a wide range of legged robots, as long as they have a URDF (Unified Robot Description Format) file. You can extend the generic `Robot` class to interact with the specific functionality of your robot.

3. **Flexibility**: While DDPG and ARS are the current machine learning algorithms in use, URE is designed to accommodate any other machine learning algorithms you might prefer. The codebase is structured to be open for the integration of other Stable Baselines3 (SB3) or homespun algorithms in the future.

4. **Deployment with ROS**: URE allows for the deployment of trained models using the Robot Operating System (ROS). Currently supporting ROS 1, URE is actively working to incorporate compatibility with ROS 2.

## Getting Started:

To get started with URE, follow these steps:

1. Clone this repository to your local machine.

2. Install the necessary dependencies. We recommend creating a virtual environment for your project to manage dependencies cleanly. See docs/`requirements.txt` for requirement list.

3. Begin your exploration with the provided examples. You can utilize the existing implementation for DDPG or extend the framework to use other machine learning algorithms.

4. Train and evaluate your legged robot models using the PyBullet simulator.

5. Deploy your trained models on real hardware or in simulation using ROS.

## Credits:

URE builds upon the work of Maurice Rahme's OpenQuadruped repository, offering a specialized environment for training and deploying legged robots. While URE is not an open-source project, it benefits from the valuable contributions of the open-source community.

## Contributions and Support:

As a closed-source project, contributions to the URE repository are not accepted. However, if you have questions or require assistance, please feel free to reach out through the issue tracker or contact the maintainers.

## License:

URE operates under a proprietary license. Please review the license agreement provided with this repository for more information.

## Disclaimer:

URE is a powerful tool for robotics development. However, please note that it is your responsibility to ensure the safety and integrity of your robot during development and deployment.
