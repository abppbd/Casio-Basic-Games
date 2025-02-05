# Casio-Basic-Games
This is list of classic games coded in Casio Basic for Casio's fx-CG50 (a.k.a Graph90+e) or similar calculators.

## Sumary
- [Upload to calculator](#how-to-upload-the-code-to-calculator)
- [Snake](#snake)
- [Minesweeper](#minesweeper)
- [Pong](pong) (broken)
- [Connect 4](#connect-4) (WIP)
- [3D renderer](#3d-renderer) (WIP)

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

Note: This implementation of minesweeper has a flood fill zero clearing algorithm !

Note2: The greater the number of mines the slower the terrain generation might be !

## Pong
/!\\ This is a two player game !

Rules: Send the ball in the adversary's camp using your pads. !

- Player 1:
  - Use one (1) and four (4) to control the left pad.
- Player 2:
  - Use minus (-) and divide (÷) to control the right pad.

Note: This game is unfinished, the collision handling has some problem and may cause the game to crash !
Note2: The buttons need to be spamed for the two players to control their pads at the same time !

## Connect 4
/!\\ This game is a work in progress !
/!\\ This is a two player game !

Rules: Align four of your chips while blocking the opponent to win.

- In Main menu:
  - Start the game by pressing enter (EXE).
- In game:
  - Use the right (>) or left (<) arrows to control the next chip.
  - Use enter (EXE) to drop your chip.
  - When a chip is droped the next player's turn begins.

## 3D renderer
/!\\ This game is a work in progress !

Rules: This is a simple demo for Doom style (a.k.a 2.5D) rendering.

- In game:
  - Use the up (^) and down (v) arrowss to move forward and backwards.
  - Use the right (>) or left (<) arrows to turn right and left.
  - Use function 2 (F2) or function 1 (F1) keys to strafe right and left.
