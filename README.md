<h1 align="center">Sudoku Solver</h1> 

<p align="center">
A classic game of Sudoku made in Pygame which uses the backtracking algorithm to visualize the board solving itself. Users can choose to either play Sudoku normally by entering in numbers. If the user presses the space bar, the backtracking algorithm begins and the board will gradually solve the complete board. The whole process is timed. 
</p>

<p align="center">
A link to an online demo version can be found here: <a href="https://repl.it/@aahmad4/Sudoku" target="_blank">repl.it/@aahmad4/Sudoku</a>
</p>

## Implementation

Change the board to any one you'd like to solve or visualize, keep in mind all 0's represent empty slots: 
```python
class Grid:
    board = [
        [7, 8, 0, 4, 0, 0, 1, 2, 0],
        [6, 0, 0, 0, 7, 5, 0, 0, 9],
        [0, 0, 0, 6, 0, 1, 0, 7, 8],
        [0, 0, 7, 0, 4, 0, 2, 6, 0],
        [0, 0, 1, 0, 5, 0, 9, 3, 0],
        [9, 0, 4, 0, 6, 0, 0, 0, 5],
        [0, 7, 0, 3, 0, 0, 0, 1, 2],
        [1, 2, 0, 0, 0, 7, 4, 0, 0],
        [0, 4, 9, 2, 0, 6, 0, 0, 7]
    ]
```

## Setup

#### Clone
```bash
git clone https://github.com/aahmad4/Sudoku-Solver
```

#### Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required packages.

```bash
pip install -r requirements.txt
```
#### Usage
```
cd Sudoku-Solver
```

Start Game:
```
python pythonSudoku.py	
```
Play:
```bash
Click on a box: Enter a number. Hit enter to confirm input. Hit the `Del` key to cancel your input.
```
Solve:
```bash
Press the space bar and the board will start visualizing and solving itself.
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
