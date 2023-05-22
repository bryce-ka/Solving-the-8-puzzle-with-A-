# Solving the 8 puzzle with A* Algorithm Implementation and Heuristic Analysis

This GitHub repository contains an implementation of the A* algorithm and an investigation into the impact of heuristic quality on search performance. The project aims to reproduce the experimental results of Russell and Norvig in the 8-puzzle domain, specifically focusing on the table shown in Figure 3.29 of their book "Artificial Intelligence: A Modern Approach" (3rd Edition).

## Background

The A* algorithm is a widely used search algorithm that combines the advantages of both uniform cost search and greedy search. It guarantees optimality (finding the shortest path) while efficiently exploring the search space by using an evaluation function that combines the cost of the current path and an estimate of the remaining cost to the goal.

Russell and Norvig's work in the 8-puzzle domain provides valuable insights into the effect of heuristic quality on the performance of the A* algorithm. By reproducing their experimental results, we aim to validate their findings and further understand the relationship between heuristic quality and search performance.

## Repository Structure

The repository is organized as follows:

- `src/`: Contains the source code for the A* algorithm implementation.
- `data/`: Includes the puzzle instances used for the experiments.
- `results/`: Stores the experimental results obtained during the reproduction of the table in Figure 3.29.
- `docs/`: Contains supplementary documentation and resources.

Certainly! Here's the updated "Getting Started" section with the provided repository link:

## Getting Started

To run the A* algorithm implementation and reproduce the experimental results, follow these steps:

1. Clone the repository: `git clone https://github.com/bryce-ka/Solving-the-8-puzzle-with-A-.git`
2. Navigate to the project directory: `cd Solving-the-8-puzzle-with-A-`
3. Compile and build the source code.
4. Run the experiments using the provided puzzle instances.
5. Analyze and interpret the results.
6. Compare the obtained results with the table in Figure 3.29.

Make sure you have the necessary dependencies installed as mentioned in the repository's documentation.

For more detailed instructions and information about the implementation, please refer to the [repository](https://github.com/bryce-ka/Solving-the-8-puzzle-with-A-).

## Usage

To reproduce the table shown in Figure 3.29, execute the `main.py` file in your chosen environment. The script imports the following modules:

- `queue`: PriorityQueue for managing the priority queue of puzzle states.
- `puzzleboard`: PuzzleBoard for representing the state of the 8-puzzle.
- `astar`: AStar for performing the A* algorithm.
- `generaterandompuzzle`: batchPuzzles for generating random puzzle instances.
- `tabulate`: tabulate for formatting the experimental results into a table.
- `ids`: IDS for performing the iterative deepening search.

The script performs the following steps:

1. Generates puzzle instances using the `batchPuzzles` function for the heuristics 'h1', 'h2', and 'ids'.
2. Collects data for each heuristic and puzzle difficulty level.
3. Writes the data into a file named `newFile.txt` using the `tabulate` function.
4. Prints the experimental results table.

## Results

The experimental results obtained from the experiments, similar to the one shown in Figure 3.29, can be found in the `newFile.txt` file. Additionally, the script prints the results in tabulated format.

