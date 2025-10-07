# Catch Me If You Can 🥷🏻👀

A fast-paced, grid-based chase game built with Python and Pygame. Control your player (the white square labeled "P") and race to catch the elusive yellow square, avoiding obstacles and managing your score in a strategic environment.

---

## How to Play

- **Player:**  
  You are the white square with "P" written on it.

- **Goal:**  
  "Touch" the moving yellow square to win. The yellow square can pass through vertical walls, making it tricky to catch.

- **Obstacles:**  
  Red squares spawn randomly and block your movement. You cannot move through these squares.

- **Bomb Mechanic:**  
  Use a bomb to clear all red squares in a 3x3 area centered on your player.  
  **Note:** Using a bomb incurs a score penalty.

- **Special Rule:**  
  If you bomb the yellow target (i.e., if the bomb explosion covers the yellow square), **you instantly lose**.

- **Score System:**  
  Your score is always negative:
  - The magnitude increases over time (the longer you take, the lower your score).
  - Each bomb used further decreases your score.

---

## Controls

| Action                        | Key(s)            |
|-------------------------------|-------------------|
| Move up                       | `K_UP`            |
| Move down                     | `K_DOWN`          |
| Move left                     | `K_LEFT`          |
| Move right                    | `K_RIGHT`         |
| Move camera up                | `K_w`             |
| Move camera down              | `K_s`             |
| Move camera left              | `K_a`             |
| Move camera right             | `K_d`             |
| Use bomb                      | `K_LSHIFT` / `K_RSHIFT` |

---

## Technical Details

- **Language:** Python 3.x
- **Framework:** Pygame
- **Platform:** Desktop (Windows, Linux, MacOS)
- **Code Structure:**
  ```
  catch-me-if-you-can-game/
  ├── game.py             # Game entry point
  ├── assets/             # Images, sounds, fonts
  ├── README.md           # Project documentation
  └── LICENSE
  ```

---

## How to Run

1. **Install Python 3.x** and Pygame:
   ```bash
   pip install pygame
   ```

2. **Clone the repository:**
   ```bash
   git clone https://github.com/Vidushi440/catch-me-if-you-can-game.git
   cd catch-me-if-you-can-game
   ```

3. **Run the game:**
   ```bash
   python game.py
   ```

---

## Additional Information

- The bomb removes all red squares in a 3x3 grid with you at the center.
- You can move both the player and the camera independently for strategic navigation.
- The game ends when you catch the yellow square or if you bomb the yellow target.
- Your final score depends on your speed and bomb usage.

---

## License

This project is released under the MIT License.

---
