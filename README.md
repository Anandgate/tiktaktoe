Tic-Tac-Toe in Python ❌⭕
A clean, lightweight, and interactive terminal-based implementation of the classic Tic-Tac-Toe game written in pure Python.

📌 Features
Two-Player Mode: Play locally with a friend on the same machine.

Input Validation: Automatically prevents invalid moves (e.g., placing a mark on an already occupied cell or entering non-numeric input).

Dynamic Board Rendering: Real-time console update after every turn.

Win & Draw Detection: Instantly evaluates horizontal, vertical, and diagonal win conditions or declares a draw when no moves remain.

Zero External Dependencies: Built using standard Python built-ins.

🛠️ Requirements
Python 3.x or higher installed on your system.

🚀 Quick Start
Clone the repository:

Bash
git clone https://github.com/your-username/tiktaktoe.git
cd tiktaktoe
Run the game:

Bash
python main.py
🎮 How to Play
The game is played on a 3x3 grid.

Positions are mapped to numbers from 1 to 9 as follows:

Plaintext
 1 | 2 | 3 
---|---|---
 4 | 5 | 6 
---|---|---
 7 | 8 | 9 
Players take turns entering the number corresponding to the cell where they want to place their mark (X or O).

The first player to get 3 marks in a row (horizontally, vertically, or diagonally) wins the game!

If all 9 cells are filled and no player has 3 in a row, the game ends in a draw.

📁 Project Structure
Plaintext
tiktaktoe/
│
├── main.py        # Core game logic and entry point
├── README.md      # Project documentation
└── .gitignore     # Git ignore configuration
🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📝 License
Distributed under the MIT License. See LICENSE for more information.
