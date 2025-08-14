# CS370
Jupyter Notebook file for the pirate intelligent agent

# README Treasure Hunt Game Project

## Project Overview
In this project, I developed an intelligent pirate agent for a treasure hunt game using deep Q-learning. The game takes place in an 8×8 maze where the pirate must navigate pathways and avoid obstacles to reach the treasure before the human player.  

The starter code provided included:
- `TreasureMaze.py` the environment with the maze layout and game mechanics  
- `GameExperience.py` the experience replay buffer to store and manage gameplay episodes 
- A partially completed Jupyter Notebook with placeholders for the agent’s learning algorithm  

I implemented:
- The Q training algorithm that drives the pirate’s decision making  
- An epsilon greedy strategy to balance exploration and exploitation  
- Experience replay integration to improve learning stability  
- The neural network training loop for Q value approximation  
- Model tuning to achieve a high and consistent win rate  

Additionally, I authored a design defense paper explaining the AI techniques, comparing human and machine problem solving, and evaluating the results.

## Connection to the Field of Computer Science

**What computer scientists do and why it matters:**  
Computer scientists design, implement, and analyze algorithms and systems that solve problems effectively. Their work matters because it drives innovation, enables automation, and powers intelligent decision making in real world applications from entertainment to healthcare to engineering.

**How I approach a problem as a computer scientist:**  
I start by breaking the problem into smaller components, analyzing requirements, and selecting appropriate algorithms or data structures. I then implement the solution systematically, test and refine it, and evaluate its performance. Reflection on results and design choices is essential for continuous improvement.

## Ethical Responsibilities

As a computer scientist, I have a responsibility to:
- Design safe, fair, and reliable systems  
- Be transparent about system capabilities and limitations  
- Reduce bias and respect user privacy  
- Ensure my solutions meet the needs of both the user and the organization  

Even in a game context, these responsibilities apply. A well designed AI opponent should provide a fair, challenging, and engaging experience without exploiting flaws or creating frustrating, unfair play conditions. Documenting decisions, validating results, and respecting user expectations are all part of building trust in AI systems.
