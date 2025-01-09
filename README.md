
### Sudoku Solver and Magic Square Solver  

This repository includes two projects that solve classic puzzles using heuristic search and optimization algorithms.

---

### **Projects Included**  

#### 1. **Magic Square Solver using A* Search Algorithm**  
This project implements the A* search algorithm to solve the 3x3 magic square puzzle, where the objective is to arrange numbers in a grid such that:  
- The sum of each row, column, and diagonal equals 15.  

**Features:**  
- Valid tile movements: Up, Down, Left, Right.  
- Heuristic cost calculation based on the difference from the target sum.  
- Optimal solution search using A* algorithm.  

---

#### 2. **Sudoku Solver using Heuristic Search**  
This project provides a heuristic-based solution for solving Sudoku puzzles by minimizing heuristic costs until a valid solution is reached.  

**Features:**  
- **Puzzle Initialization:** Handles incomplete 9x9 Sudoku grids as input.  
- **Solution Validation:** Ensures uniqueness across rows, columns, and 3x3 subgrids.  
- **Heuristic Cost Calculation:** Measures the number of remaining empty cells to prioritize states.  
- **Heuristic Search Algorithm:** Uses a priority queue for iterative exploration of optimal solutions.  
- **Interactive Display:** Outputs the puzzle state as it is being solved.  

**Example Input:**  
```python
puzzle = [[2,3,0,4,1,5,0,6,8], 
          [0,8,0,2,3,6,5,1,9],
          [1,6,0,9,8,7,2,3,4],
          [3,1,7,0,9,4,0,2,5],
          [4,5,8,1,2,0,6,9,7], 
          [9,2,6,0,5,8,3,0,1],
          [0,0,0,5,0,0,1,0,2],
          [0,0,0,8,4,2,9,0,3],
          [5,9,2,3,7,1,4,8,6]]
```  

---

### **Usage**  
- Clone this repository and explore both puzzle solvers.  
