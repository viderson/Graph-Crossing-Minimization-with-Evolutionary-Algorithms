# Graph Crossing Minimization using Evolutionary Algorithm 🌐🧬

This project focuses on minimizing the number of **edge crossings** in a graph layout using an **evolutionary algorithm**, implemented with the `DEAP` Python library.

## 🎯 Objective

Given a graph defined by its vertices and edges, the goal is to find a layout that **minimizes the number of edge crossings**, improving the clarity and aesthetics of graph visualizations.

## 📁 Project Structure

```
project/
├── Project_algorytm_ewolucyjny.ipynb  # Main notebook with full implementation
└── README.md
```

## 🧠 Method

The solution uses a **genetic algorithm** to optimize node positions in 2D space, minimizing edge intersections. The fitness function counts the number of line segment crossings.

### Key steps:

1. Graph representation using edge list
2. Encoding node positions as individuals (chromosomes)
3. Defining a fitness function based on crossing count
4. Applying selection, crossover, and mutation
5. Iterative improvement using evolutionary pressure

## 🔧 Libraries Used

- `DEAP` – Evolutionary algorithm toolkit
- `NumPy`, `Pandas`
- `Matplotlib` – Visualization
- `TQDM` – Progress bars

## 📊 Visual Output

The notebook generates:
- Initial and optimized graph layouts
- Graphs showing the number of crossings per generation

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib deap tqdm
   ```

2. Open the notebook:
   ```bash
   jupyter notebook Project_algorytm_ewolucyjny.ipynb
   ```

3. Run all cells to:
   - Initialize the graph
   - Evolve solutions
   - Visualize results

## 🎓 Learning Outcomes

- Apply evolutionary algorithms to optimization problems
- Understand graph drawing aesthetics
- Customize DEAP for non-trivial objective functions
- Practice modular, interpretable code

## 📌 Credits

- Author: [Your Name]
- Based on classical graph theory and evolutionary optimization techniques

---

Feel free to fork, use, and adapt ⭐
