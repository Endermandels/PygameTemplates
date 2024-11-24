# Closed #

# Open #

## Top Down 2D ##

- [1] Game class
    - Load assets
    - Init misc game info (like constants and such)
- [2] Scene class
    - Draw to screen (Do NOT scale images properly; too much work)
    - Switch between substates
    - Switch between scenes
- [3] Entity class
    - Position, image, drawing priority
- [4] HUD
    - Toggle HUD display
    - Display info
    - Take input in shell style
    - Create functions to handle input
- [5] Mob Entity class
    - Movement
- [6] Player Mob class
    - Movement
    - Input
- [7] Play Scene class
    - Create entity arenas and spawn entities
    - Update and render entities
    - Pause command to bring up pause menu
        - Resume
        - Options
        - Go back to Menu Scene
        - Quit
- [8] Menu Scene class
    - Create Button class (pygame_widgets?)
    - Choose between different button options
        - Play (switch to Play Scene)
        - How to Play (switch to How to Play Scene)
        - Options (switch to Options Scene)
        - Quit (quit the game)
- [9] Title Scene class
    - Display title screen
    - Make title screen skippable
    - Transition to Menu Scene
- [10] How to Play Scene
    - Display how to play text (read from text file)
    - Button for switching back to Menu Scene
- [11] Options Scene
    - Show adjustable options
        - Volume
        - Full Screen

# Backlog #
