# AI Dino Game

Welcome to the AI Dino Game project! This repository contains a Python implementation of the classic Chrome Dino game that plays itself using artificial intelligence. The project utilizes neural networks, genetic algorithms, and reinforcement learning to create an AI that can play the Dino game autonomously.

## Features

- **Neural Networks**: The AI uses neural networks to make real-time decisions while playing the game.
- **Genetic Algorithms**: The algorithm evolves the neural networks over generations, improving their performance.
- **Reinforcement Learning**: The AI learns from its experiences, optimizing its gameplay strategy.

## Getting Started

To get started with this project, follow the steps below:

### Prerequisites

- Python 3.x
- Pygame
- NEAT-Python

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mali-98/AI-Dino-Game.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd AI-Dino-Game
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Game

1. **Run the AI**:
   ```bash
   python main.py
   ```

2. **Watch the AI Play**:
   - After running the script, the AI will start playing the game and evolving over generations.
   - You can observe the AI's progress as it learns to avoid obstacles and improve its score.

## Project Structure

- `dino_ai.py`: Main script to run the game and train the AI.
- `game/`: Contains the game logic and assets.
- `config-feedforward.txt`: Configuration file for the NEAT algorithm.
- `requirements.txt`: List of dependencies for the project.

## How It Works

1. **Initialization**: The game initializes with a population of neural networks.
2. **Evaluation**: Each neural network controls a dinosaur, attempting to avoid obstacles.
3. **Selection**: The algorithm selects the best-performing networks based on their fitness scores.
4. **Crossover and Mutation**: New generations of neural networks are created by combining and mutating the best networks.
5. **Iteration**: The process repeats over many generations, progressively improving the AI's performance.

## Contributing

We welcome contributions to enhance this project. Feel free to open issues or submit pull requests with improvements, bug fixes, or new features.
Feel free to customize the content to better fit your project's specifics and your preferences.
