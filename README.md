## Description 

This package contains code to run a genetic algorithm. Because the algorithm is computationally inexpensive, it is useful for optimizations where the objective function can be queried many times such as hyperparameter tuning or fitting a model. This genetic algorithm contains four steps:

<p align="center">
<img src="/Images/GA.jpg" width="350" height="300">
</p>

- **Evaluation:** Sorting the candidates based on their fitness score
- **Selection:** Selecting the candidates that are passed to the next round according to their fitness score. This algorithm uses a roulette wheel approach, where the probability of being selected is proportional to the candidate's fitness
- **Crossover:** The information from two candidates that were selected from the previous step are randomly shuffled between each other to form "offspring" candidates 
- **Mutation:** A random change in the offspring candidates is introduced which is controlled by a hyperparameter. A mutation rate closer to 0 will favor exploitation and a mutation rate closer to 1 will favor exploration 

### Instructions

The best way to use this algorithm is to open the jupyter notebook called Run_GA.ipynb and follow the example given in the notebook.
