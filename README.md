# A* Algorithm Implementation for Square Puzzles
Calculates the average steps to solution and nodes expanded using the A* algorithm given 3 distinct heuristics for the solving of 8 and 15-puzzles. 

## Heuristics
The algorithm will use the following heuristic logic for calculating distances:
- `h1`: Simple misplaced tiles count comparison to goal state.
- `h2`: Manhattan distance heuristic.
- `h3`: Pattern database heuristic (for 8-Puzzle)/Manhattan Linear conflict heuristic (for 15-Puzzle)

## Setup
1. Clone the repository:
```bash
git clone https://github.com/brianpacouloute/assignment_1_part_2.git
```

2. Change to directory:
```bash
cd assignment_1_part_2
```

### Running the 8-Puzzle Calculations

3. a) Run the Python script via Python installed from python.org:
```bash
py 8puzzle.py
```

b) Run the Python script via Python installed from Microsoft Store:
```bash
python 8puzzle.py
```

### Running the 15-Puzzle Calculations

4. a) Run the Python script via Python installed from python.org:
```bash
py 15puzzle.py
```

b) Run the Python script via Python installed from Microsoft Store:
```bash
python 15puzzle.py
```