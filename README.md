#  Snake Game

A classic **Snake Game** built using **Python Turtle Graphics**.
The project is divided into multiple Python files to keep the code organized and modular.

##  Features

*  Snake movement using keyboard controls
*  Randomly generated food
*  Score tracking
*  Collision detection
*  High-score tracking
*  Game-over detection
* Modular project structure

##  Technologies Used

* **Python 3**
* **Turtle Graphics**
* **Object-Oriented Programming (OOP)**

##  Project Structure

```text
Snake-Game/
│
├── main.py
├── snake.py
├── food.py
├── scoreboard.py
└── README.md
```

### `main.py`

The main file that runs the game and handles the game loop, screen setup, keyboard controls, and collision detection.

### `snake.py`

Contains the `Snake` class and handles:

* Creating the snake
* Snake movement
* Extending the snake
* Resetting the snake
* Direction control

### `food.py`

Contains the `Food` class and handles:

* Creating food
* Random food positioning
* Moving food after it is eaten

### `scoreboard.py`

Contains the `Scoreboard` class and handles:

* Current score
* High score
* Displaying the score
* Updating the high score

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/SurajDaggu-05/Snake-Game.git
```

### 2. Navigate to the project folder

```bash
cd Snake-Game
```

### 3. Run the game

```bash
python main.py
```

##  Controls

| Key            | Action     |
| -------------- | ---------- |
|  Up Arrow    | Move Up    |
|  Down Arrow  | Move Down  |
|  Left Arrow  | Move Left  |
| Right Arrow | Move Right |

##  What I Learned

While building this project, I practiced:

* Python classes and objects
* Object-oriented programming
* Importing and working with multiple Python modules
* Lists and data structures
* Functions and methods
* Keyboard event handling
* Collision detection
* Game loops
* File organization and modular programming
* Using Git and GitHub to manage a project


## Future Improvements

Some features I may add in the future:

* Different difficulty levels
* Pause and resume functionality
* Sound effects
* Special food items
* More advanced graphics
* Start/restart screen

##  Author

**Suraj Daggu**

Built as a Python learning project while practicing game development and object-oriented programming.

---

If you like this project, consider giving the repository a star!
