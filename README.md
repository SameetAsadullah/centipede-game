<h1 align="center">Centipede Game</h1>

### Description
An arcade-style C++ game rendered with GLUT/OpenGL. The implementation coordinates player movement, projectile and enemy collisions, destructible mushrooms, scoring, lives, persistent high scores, and a centipede-splitting mechanic triggered by targeted hits.

### Repository layout

```text
data/     Persistent high-score state
docs/     Class diagram
extras/   Menu and gameplay screenshots
include/  Game class and graphics headers
scripts/  Dependency setup
src/      Game implementation and entry point
```

### Build and run
1. Install the required Ubuntu packages:
    ```
    bash scripts/install-dependencies.sh
    ```  

2. Build the game from the repository root:
    ```
    make
    ```
    
3. Run the game from the repository root so it can access `data/highscore.txt`:
    ```
    make run
    ```
    <div align="center">
      <img src = "https://github.com/SameetAsadullah/centipede-game/blob/main/extras/menu-ss.png" alt = "" width="900px"/>
    </div>
    
4. Use the `Right Arrow` to select a menu option, the arrow keys to move, and the space bar to fire:
    <div align="center">
      <img src = "https://github.com/SameetAsadullah/centipede-game/blob/main/extras/gameplay-ss-1.png" alt = "" width="900px"/>
    </div>
    <br/>

    <div align="center">
      <img src = "https://github.com/SameetAsadullah/centipede-game/blob/main/extras/gameplay-ss-2.png" alt = "" width="900px"/>
    </div>
    <br/>

    <div align="center">
      <img src = "https://github.com/SameetAsadullah/centipede-game/blob/main/extras/gameplay-ss-3.png" alt = "" width="900px"/>
    </div>
