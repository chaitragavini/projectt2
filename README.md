🪨📄✂️ Rock-Paper-Scissors Game (Python)
This is a simple Rock-Paper-Scissors game implemented in Python. The user plays against the computer by choosing one of three options: paper, rock, or scissors.

🎮 How to Play
Run the program.

When prompted, enter:

0 for paper

1 for rock

2 for scissors

The computer will randomly choose one of the options.

The result will be displayed: You win, You lose, or Draw.

🧠 Game Rules
Paper beats rock

Rock beats scissors

Scissors beat paper

Same choices result in a draw

🧾 Example Output
lua
Copy
Edit
what do you choose? type 0 for paper,1 for rock,2 for scissors: 0
   ___
---'   _)_
          __)
          ___)
         ___)
---.____)
Computer chose:
    ___
---'   __)
      (___)
      (___)
      (__)
---._(__)
You win!
🧑‍💻 Code Explanation
Game choices are represented using ASCII art.

The computer's choice is generated using random.randint(0, 2).

Input is validated to ensure the user enters a number between 0 and 2.

The winner is decided using conditional logic.
