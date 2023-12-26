## ANN-PSO Integration Project for Dataset Optimization

### Introduction
This project explores the deep learning fundamentals by constructing an Artificial Neural Network (ANN) and Particle Swarm Optimization (PSO) from scratch. The primary aim is to optimize an ANN for a specific dataset using a PSO algorithm with informants, examining the effects of different hyperparameters on the ANN's performance.

### Project Structure
- **activation.py**: Implements various activation functions (linear, softmax, sigmoid, tanh, ReLU) essential for ANN operations.
- **ANNbuilder.py**: Constructs the ANN architecture, allowing for the creation of multi-layered networks.
- **loss.py**: Contains loss functions to evaluate the ANN's performance.
- **layer.py**: Defines the layer structure of the ANN.
- **network.py**: Main methods of the neural network, including layer addition, forward propagation, weight setting, and total weight computation.
- **particle.py**: Details the properties and behaviors of particles in the PSO framework, including informant best position updates.
- **pso.py**: Core Particle Swarm Optimization algorithm implementation, managing swarm particle positions and global best loss computation.
- **swarm.py**: Manages swarm behaviors in PSO, including initialization, global best position and loss evaluation, and particle updates.
- **main files**: Four main files for binary classification, multiclass classification, regression, and parameters testing. Each is available as a Python file and a Jupyter Notebook.

### Experimental Investigation
- **PSO Parameters Adjustment**: Examines the impact of population size and iteration number on ANN performance.
- **Coefficient Influence in PSO Velocity Equation**: Investigates the effects of cognitive, social, and informant influence coefficients on PSO learning dynamics.
- **ANN Architectures and Activation Functions**: Tests various network architectures and activation function combinations to assess their impact on network performance.

### Discussion
The project reveals the sensitivity of the PSO algorithm to hyperparameter settings, highlighting the significance of balancing individual experience with social information sharing. The results show a robustness of the ANN model, with a high degree of flexibility in terms of architecture and function adaptability.

### Conclusion
This study underlines the importance of fine-tuning PSO parameters and structuring ANN architecture for optimal performance. Future work may focus on applying these methods to more diverse datasets and exploring adaptive PSO mechanisms for enhanced exploration and exploitation balance.

### How to Use
1. Install required libraries.
2. Run the main files for specific tasks (binary classification, multiclass classification, regression, or parameters testing).
3. Adjust hyperparameters in the `pso.py` and `ANNbuilder.py` files as needed for different experiments.

### Contributions
Contributions to this project are welcome. Please follow the guidelines provided for code contributions and discussions.
