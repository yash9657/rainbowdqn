# Rainbow DQN Implementation for Atari Games

## Overview
This project implements the Rainbow algorithm, an advanced reinforcement learning framework that combines multiple state-of-the-art improvements to Deep Q-Networks (DQN). The implementation focuses on training agents to play Atari games using a combination of several cutting-edge techniques in reinforcement learning.

## Key Features
- **Double Q-Learning**: Reduces overestimation bias in Q-value estimation
- **Prioritized Experience Replay**: Prioritizes important transitions for more efficient learning
- **Dueling Network Architectures**: Separates value and advantage streams for better policy evaluation
- **Noisy Nets**: Introduces noise to network parameters for better exploration
- **Multi-Step Learning**: Uses n-step returns for more efficient value estimation
- **Distributional Q-Learning**: Learns the distribution of returns instead of expected returns

## Project Structure
```
.
├── CS_258_Final_Project.ipynb      # Main implementation notebook
├── saved_models/                    # Directory for trained model checkpoints
├── videos/                         # Directory for gameplay recordings
└── Final Project Report.pdf        # Detailed project report
```

## Requirements
- Python 3.x
- PyTorch
- Gymnasium (formerly OpenAI Gym)
- NumPy
- Matplotlib
- Other dependencies as specified in the notebook

## Usage
1. Open the `CS_258_Final_Project.ipynb` notebook
2. Follow the implementation steps in the notebook
3. Run the training and evaluation cells
4. View results and visualizations

## Results
The implementation demonstrates improved performance over traditional DQN through:
- Better sample efficiency
- More stable learning
- Higher final performance
- Improved exploration strategies

## Author
- **Yash Bhalgat**
- SID: 862465699
- Email: ybhal001@ucr.edu

## License
This project is part of a course assignment (CS 258) and is intended for educational purposes.

## References
- Rainbow: Combining Improvements in Deep Reinforcement Learning (Hessel et al., 2017)
- Playing Atari with Deep Reinforcement Learning (Mnih et al., 2013)
- Deep Reinforcement Learning with Double Q-learning (Van Hasselt et al., 2015) 