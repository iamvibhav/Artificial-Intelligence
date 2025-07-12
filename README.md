# 🤖 AI Algorithms Portfolio

A comprehensive collection of Artificial Intelligence algorithms and problem-solving techniques implemented in Python. This portfolio demonstrates various search strategies, pathfinding algorithms, constraint satisfaction problems, and game-playing AI.

## 📋 Table of Contents

- [Overview](#overview)
- [Projects](#projects)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Algorithm Comparisons](#algorithm-comparisons)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

This repository contains implementations of fundamental AI algorithms and problem-solving techniques. Each project is designed to demonstrate different aspects of artificial intelligence, from basic search algorithms to complex constraint satisfaction problems.

## 🚀 Projects

### 1. **Algorithm Comparison** (`ai-algo-compare.ipynb`)
Comprehensive comparison of different pathfinding algorithms on a grid-based environment.

**Features:**
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Uniform Cost Search (UCS)
- Best-First Search
- A* Search Algorithm
- Performance visualization and analysis
- Path length, nodes explored, and execution time metrics

**Key Insights:**
- A* typically provides the most efficient path
- BFS guarantees shortest path but explores more nodes
- DFS is memory efficient but may not find optimal path

### 2. **Robot Path Planning** (`ai-robot-path.ipynb`)
Advanced pathfinding for robot navigation with multiple algorithms and heuristics.

**Features:**
- A* with Manhattan and Euclidean heuristics
- Breadth-First Search
- Uniform Cost Search
- Visual path representation
- Obstacle avoidance
- Diagonal movement support

### 3. **Sudoku Solver** (`sudoku_solver.ipynb`)
Constraint satisfaction problem solver using A* algorithm.

**Features:**
- A* search with heuristic optimization
- Constraint checking (row, column, box)
- State exploration tracking
- Performance metrics
- Beautiful board visualization

### 4. **Water Jug Problem** (`ai-water-jug.ipynb`)
Game-playing AI using Minimax algorithm with Alpha-Beta pruning.

**Features:**
- Minimax algorithm implementation
- Alpha-Beta pruning for optimization
- Interactive game mode
- AI vs Human gameplay
- Multiple jug capacities support

### 5. **Bidirectional Search** (`ai-bidirectional-algo.ipynb`)
Efficient search algorithm that explores from both start and goal simultaneously.

**Features:**
- Bidirectional BFS implementation
- Meeting point detection
- Path reconstruction
- Performance comparison with unidirectional search

### 6. **Depth-Limited Search Tree** (`ai-dlsTree.ipynb`)
Tree-based search with depth limitation to prevent infinite exploration.

**Features:**
- Depth-limited search implementation
- Tree visualization
- Depth control mechanisms
- Memory-efficient exploration

### 7. **Best-First Search** (`ai-bestfs.ipynb`)
Heuristic-based search algorithm prioritizing promising nodes.

**Features:**
- Greedy best-first search
- Heuristic function implementation
- Priority queue usage
- Path optimization

### 8. **Uniform Cost Search** (`ai-ucs-algo.ipynb`)
Cost-based search algorithm finding optimal paths.

**Features:**
- Dijkstra's algorithm implementation
- Cost-based pathfinding
- Priority queue optimization
- Optimal path guarantee

### 9. **A* Algorithm** (`ai-astar-algo.ipynb`)
Advanced heuristic search combining cost and heuristic functions.

**Features:**
- A* implementation with f(n) = g(n) + h(n)
- Multiple heuristic options
- Optimal path finding
- Performance optimization

### 10. **BFS & DFS Implementation** (`ai-bfs-dfs.ipynb`)
Basic search algorithms with visualization.

**Features:**
- Breadth-First Search
- Depth-First Search
- Graph traversal visualization
- Path finding capabilities

### 11. **Graph Algorithms** (`ai-graph.ipynb`)
Graph-based algorithms and data structures.

**Features:**
- Graph representation
- Traversal algorithms
- Path finding
- Connected components

### 12. **Maze Solver** (`ai-maze-solver.ipynb`)
Maze solving using various AI algorithms.

**Features:**
- Multiple algorithm implementations
- Maze generation
- Solution visualization
- Performance analysis

### 13. **Water Jug Problem (Alternative)** (`ai-waterJug.ipynb`)
Alternative implementation of the water jug problem.

**Features:**
- Different approach to the same problem
- State space exploration
- Solution finding algorithms

## 🛠️ Technologies Used

- **Python 3.x**
- **Jupyter Notebooks**
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Heapq** - Priority queue implementation
- **Collections** - Data structures
- **Time** - Performance measurement

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd ai-algorithms-portfolio
   ```

2. **Install required dependencies:**
   ```bash
   pip install jupyter numpy matplotlib
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

## 🎮 Usage

### Running Individual Projects

Each project is contained in a Jupyter notebook. To run a specific project:

1. Open the desired `.ipynb` file in Jupyter
2. Run all cells (Cell → Run All)
3. Follow the interactive prompts where applicable

### Example: Running Algorithm Comparison

```python
# Open ai-algo-compare.ipynb
# Run all cells to see:
# - Algorithm implementations
# - Performance comparison
# - Visualization of results
```

### Example: Playing Water Jug Game

```python
# Open ai-water-jug.ipynb
# Run the game and interact with the AI
# Enter jug capacities and target volume
# Play against the AI using minimax algorithm
```

## 📊 Algorithm Comparisons

### Performance Metrics

| Algorithm | Time Complexity | Space Complexity | Optimality |
|-----------|----------------|------------------|------------|
| BFS | O(V + E) | O(V) | ✅ Optimal |
| DFS | O(V + E) | O(V) | ❌ Not Optimal |
| UCS | O((V + E) log V) | O(V) | ✅ Optimal |
| A* | O((V + E) log V) | O(V) | ✅ Optimal |
| Best-First | O((V + E) log V) | O(V) | ❌ Not Optimal |

### Use Cases

- **BFS**: Shortest path problems, web crawling
- **DFS**: Maze solving, topological sorting
- **UCS**: Weighted graph shortest path
- **A***: Game pathfinding, GPS navigation
- **Best-First**: Heuristic-based problems

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classic AI algorithms and problem-solving techniques
- Built for educational purposes and algorithm understanding
- Special thanks to the AI/ML community for continuous learning resources

---

**Happy Coding! 🚀**

*This portfolio demonstrates the power and beauty of artificial intelligence algorithms in solving real-world problems.* 
