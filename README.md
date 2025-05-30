
# AI Search Algorithms Project

This repository contains an AI project focused on implementing and comparing various search algorithms for solving the Light Puzzle problem. The project includes code implementations, performance analysis, and detailed reports.

**Course**: Artificial Intelligence – Autumn 2024  
**University of Tehran | School of Electrical & Computer Engineering**


---

## Project Contents

1. **notebook.ipynb** - The Jupyter Notebook with detailed implementations of BFS, IDS, A*, and Weighted A* algorithms.
2. **report.pdf** - A comprehensive project report discussing the algorithms, heuristics, and performance analysis.
3. **table.txt** - A summary of test results, including nodes visited, time taken, and optimal solutions found by different algorithms.

---

## Algorithms Implemented

- **BFS (Breadth-First Search):** Guarantees optimal solutions but may require significant memory.
- **IDS (Iterative Deepening Search):** Combines DFS's space efficiency with BFS's completeness.
- **A* Search:** Uses heuristics to guide the search process efficiently.
- **Weighted A* Search:** A variation of A* that balances exploration and exploitation using weighted heuristics.

---

## Heuristics Used

1. **Heuristic 1:** Average distance between lit lamps (non-admissible).
2. **Heuristic 2:** Number of lit lamps (non-admissible).
3. **Heuristic 3:** Scaled version of Heuristic 2 for better admissibility.
4. **Heuristic 4:** Selective counting of lit lamps in specific patterns (non-admissible).

---

## Test Results Summary

- **Test Cases:** Results from various algorithms compared across metrics like nodes visited, time taken, and success rates.
- **Performance Highlights:**
  - **BFS & IDS:** Provide optimal solutions but are slow and memory-intensive for larger puzzles.
  - **A* Search:** Found optimal solutions faster when paired with admissible heuristics.
  - **Weighted A* Search:** Improved performance by reducing search depth and expanding fewer nodes.

Refer to **table.txt** for the full set of results.
