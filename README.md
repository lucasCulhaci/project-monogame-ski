# HoGent – Software Design 2 - Monogame Ski

## How to start this game?

1. Download the full repository.
2. Open the project in your IDE, using "monogame_ski_lucas_culhaci.csproj".
3. Have fun!

## How to play this game?

There are several game modes in this game.

1. **(3 Skiers):** 3 skiers that you control simultaneously on a track without obstacles.
2. **(Enemies / 1 skier):** 1 skier gliding through the track with obstacles.
3. **(Enemies / 3 skiers):** 3 skiers gliding through the track with obstacles.
4. **(Enemies / 2 players):** 2 players, each with their own skier, gliding through the track with obstacles.

There is also a bonus game mode in this game! You can find how to start this game mode within the code itself!

### Keyboard Inputs

- **Player 1:** ZQSD
- **Player 2:** Arrow keys
- **During gameplay:**
  - **Pause Game:** P
  - **Return to Menu:** M
- **Exit Game:** ESC

### Possible Error Messages

> The command "dotnet tool restore" exited with code 1.

![](./Images/errorMesssage-1.png)

##### How to fix this?

1. Close the project and open the folder **monogame-ski-lucas-culhaci** and navigate to the **.config** folder. If this is not visible, you can type `\.config` in the search bar after the current path and then press "enter".

![](./Images/path-1.png)

2. Right-click on the file **dotnet-tools.json**.
3. Choose **Properties**.
4. At the bottom of the 'General' tab, you will see a message: "This file came from another computer...".
5. Check the **Unblock** box and click "OK".
6. Restart the project!

# Contact

For any issues regarding this project, you can create a new issue in this GitHub repository, or you can contact me via email: lucas.culhaci@student.hogent.be
