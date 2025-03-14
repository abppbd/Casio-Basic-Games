# Casio-Basic-Games
This is a list of classic games coded by [abppbd](https://github.com/abppbd) in Casio Basic for Casio's fx-CG50 (a.k.a Graph90+e) or similar calculators.

## Sumary
- [Upload to calculator](#how-to-upload-the-code-to-calculator)
- [Snake](#snake)
- [Minesweeper](#minesweeper)
- [Tic Tac Toe](#tic-tac-toe)
- [Connect 4](#connect-4)
- [3D renderer](#3d-renderer) (WIP)
- [Pong](#pong) (broken)

## How to upload the code to calculator
### With the text file (.txt)
- Connect the calculator to a computer with the provided USB cable.
- On the calculator a "Connection mode" prompt appears, select "USB Flash" (F1).
- Use file explorer on the computer to go to the calculator USB drive in "D:\\SAVE-F\\PROGRAM".
- Copy the .txt file in the directory.
- Eject the calculator USB Drive.
- On the calculator, go in the "Program" app (MENU > B).
- Import the program by pressing "LOAD" (F6 > F4) and navigate to the file in "SAVE-F\\PROGRAM\\game.txt"

The Program is now loaded and ready to be played in the "Program" app (MENU > B)!

### With the Casio basic file (.g3m)
- Connect the calculator to a computer with the provided USB cable.
- On the calculator a "Connection mode" prompt appears", select "USB Flash" (F1).
- Use file explorer on the computer to go to the calculator USB drive in "D:\\@MainMem\\PROGRAM".
- Copy the .g3m file in the directory.
- Eject the calculator USB Drive.

The Program is now loaded and ready to be played in the "Program" app (MENU > B)!

## Snake
Rules: Collect as much food as possible without crashing your snake in the walls or itself !

Controls:
- In the main menu:
  - Use the up (^) and down (v) arrows to select an option.
  - Speed: Use the right (>) or left (<) arrows to control the speed.
  - Start: Press enter (EXE) to start the game.
- In game:
  - Use the directional arrows (< ^ > v) to control the snake and collect the food.

[Text code](https://raw.githubusercontent.com/abppbd/Casio-Basic-Games/refs/heads/main/Text%20code/SNAKE.txt) | [g3m code](https://github.com/abppbd/Casio-Basic-Games/raw/refs/heads/main/g3m%20code/SNAKE.g3m)

Note: You can hold pressed the arrow in the same direction as the snake head to get a speed boost ! 
 
## MineSweeper
Rules: Clear the terrain by uncovering every non-mine tiles without triggering any of the mines (you can place flags to mark and secure the mines) !

- In the main menu:
  - Use the up (^) and down (v) arrows to select an option.
  - Mines: Use the right (>) or left (<) arrows to control the amount of mines (1 to 99).
  - Start: Press enter (EXE), right (>) arrow or zero(0) to start the game.
- In game:
  - Use the directional arrows (< ^ > v) to control the cursor.
  - Use enter (EXE) to uncover a tile. (The 1st press is always safe and will generate the mines)
  - Use zero (0) to flag a tile. (Not all the mines need to be flaged but all non-mines tiles need to be uncovered)

[Text code](https://github.com/abppbd/Casio-Basic-Games/raw/refs/heads/main/Text%20code/MINESWPR.txt) | [g3m code](https://github.com/abppbd/Casio-Basic-Games/raw/refs/heads/main/g3m%20code/MINESWPR.g3m)

Note: This implementation of minesweeper has a flood fill zero clearing algorithm !
Note2: The greater the number of mines the slower the terrain generation might be !

## Tic Tac Toe
/!\\ This is a two player game !

Rules: Win a match by aligning 3 of your marks (X or O) down, across or in a diagonal. This game is endless, play until the turnament is done.

- In the main menu:
  - Start: Press enter (EXE).
- In game:
  - Use the numerical pad (0 to 9) to fill in the corresponding cell on the screen.
  - Use enter (EXE) to proceed to the next match (a tally is keept of ties, X's wins & O's wins).
  - Use EXIT to finish the turnament (the final tally will be shown).
  - When a cell is marked the next player's turn begins.

[Text code](https://github.com/abppbd/Casio-Basic-Games/raw/refs/heads/main/Text%20code/TICTACTO.txt) | [g3m code](https://github.com/abppbd/Casio-Basic-Games/raw/refs/heads/main/g3m%20code/TICTACTO.g3m)

## Connect 4
/!\\ This is a two player game !

Rules: Align four of your chips while blocking the opponent's chips to win.

- In Main menu:
  - Start: Pressing enter (EXE).
- In game:
  - Use the right (>) or left (<) arrows to control your chip (black or white).
  - Use enter (EXE) to drop your chip (a pipe shows you where the chip will fall).
  - When a chip is droped the next player's turn begins.

[Text code](https://github.com/abppbd/Casio-Basic-Games/raw/refs/heads/main/Text%20code/CONNECT4.txt) | [g3m code](https://github.com/abppbd/Casio-Basic-Games/raw/refs/heads/main/g3m%20code/CONNECT4.g3m)

## 3D renderer
/!\\ This game is a work in progress !

Rules: This is a simple demo for Doom style (a.k.a 2.5D) rendering.

- In game:
  - Use the up (^) and down (v) arrowss to move forward and backwards.
  - Use the right (>) or left (<) arrows to turn right and left.
  - Use function 2 (F2) or function 1 (F1) keys to strafe right and left.

[Text code](https://github.com/abppbd/Casio-Basic-Games/raw/refs/heads/main/Text%20code/3DRENDER.txt) | [g3m code](https://github.com/abppbd/Casio-Basic-Games/raw/refs/heads/main/g3m%20code/SNAKE.g3m)

## Pong
/!\\ This is a two player game !

Rules: Send the ball in the adversary's camp using your pads. !

- Player 1:
  - Use one (1) and four (4) to control the left pad.
- Player 2:
  - Use minus (-) and divide (÷) to control the right pad.

[Text code](https://github.com/abppbd/Casio-Basic-Games/raw/refs/heads/main/Text%20code/PONG.txt) | [g3m code](https://github.com/abppbd/Casio-Basic-Games/raw/refs/heads/main/g3m%20code/PONG.g3m)

Note: This game is unfinished, the collision handling has some problem and may cause the game to crash !
Note2: The buttons need to be spamed for the two players to control their pads at the same time !

