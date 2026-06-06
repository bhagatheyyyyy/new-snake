# 🐍 Bhagath's Snake Game

## About This Project

This project is my own version of the classic Snake Game built using HTML, CSS, and JavaScript.

I wanted to create a game that was simple to understand but challenging enough to help me learn more about JavaScript and game development. Instead of using game engines or external libraries, I decided to build everything from scratch using the HTML Canvas element and vanilla JavaScript.

The result is a fully playable browser game where the player controls a snake, collects apples, increases their score, and tries to survive as long as possible.

---

## Why I Built It

I enjoy learning programming through practical projects. After learning the basics of HTML, CSS, and JavaScript, I wanted to build something interactive rather than another static webpage.

The Snake Game was a great project because it combines several important programming concepts:

* Keyboard input handling
* Collision detection
* Game loops
* Object manipulation
* Arrays
* Real-time updates
* Canvas drawing

Building this project helped me understand how many classic games work behind the scenes.

---

## Gameplay

The game starts with a small snake positioned on the board.

The player's objective is to collect apples while avoiding collisions.

Every time an apple is collected:

* The score increases
* The snake grows longer
* A new apple appears at a random location

As the snake grows, navigating the board becomes more difficult because the player must avoid colliding with the snake's own body.

The game ends when:

* The snake hits a wall
* The snake collides with itself

Instead of using a browser alert, the game displays a custom Game Over screen that shows the player's score and provides a restart button.

---

## Features

### Current Features

* Classic Snake gameplay
* Smooth keyboard controls
* Real-time score counter
* Growing snake body
* Random apple spawning
* Collision detection
* Custom Game Over popup
* Restart button
* Clean user interface
* Built with pure JavaScript
* No external libraries or frameworks

---

## Controls

| Key            | Action     |
| -------------- | ---------- |
| ⬆️ Arrow Up    | Move Up    |
| ⬇️ Arrow Down  | Move Down  |
| ⬅️ Arrow Left  | Move Left  |
| ➡️ Arrow Right | Move Right |

---

## Technologies Used

### HTML5

HTML is used to create the structure of the page, including the game canvas, score display, and Game Over popup.

### CSS3

CSS is used to style the game and create a clean visual design. It is also responsible for animations and popup effects.

### JavaScript

JavaScript powers the entire game logic, including:

* Snake movement
* Apple generation
* Score tracking
* Collision detection
* Restart system
* Game state management

### HTML Canvas

The snake and apples are drawn directly onto a canvas element, allowing smooth rendering and updates.

---

## Project Structure

```text
snake-game/
│
├── index.html
├── style.css
├── README.md
└── assets/
```

---

## What I Learned

This project taught me several important concepts:

### JavaScript Fundamentals

I gained experience working with:

* Arrays
* Objects
* Functions
* Event listeners
* Timers

### Game Development Concepts

I learned how to implement:

* Game loops
* Collision detection
* Player input handling
* Dynamic object generation
* State management

### Problem Solving

One of the biggest challenges was making sure the snake behaved correctly when changing directions and detecting collisions accurately.

Working through these problems helped improve my debugging skills and logical thinking.

---

## Challenges Faced

While developing this game, I encountered several challenges:

* Preventing the snake from reversing into itself
* Detecting self-collisions correctly
* Managing game states after Game Over
* Creating a restart system without refreshing the page
* Drawing game objects smoothly using Canvas

Each challenge helped me better understand how interactive web applications work.

---

## Future Improvements

Although the game is fully playable, I have several ideas for future updates:

* High score saving using localStorage
* Mobile touch controls
* Sound effects
* Background music
* Difficulty levels
* Pause and resume feature
* Multiple themes
* Different snake skins
* Achievement system
* Leaderboard support

---

## Screenshots

You can add screenshots here in the future:

```md
![Gameplay Screenshot](screenshot.png)
```

Screenshots make it easier for visitors to quickly understand the project.

---

## About Me

My name is **Bhagath P**, and I am a student from Kerala, India.

I enjoy coding, reading books, astronomy, filmmaking, acting, and creating content. I like building projects that help me learn new skills and explore technology in a practical way.

This Snake Game is one of the projects I created as part of my programming journey.

---

## Running the Project

To run the game locally:

1. Download or clone this repository.
2. Make sure all files remain in the same folder.
3. Open `index.html` in a web browser.
4. Start playing.

No installation or setup is required.

---

## License

This project is available for educational and personal use.

Feel free to explore the source code, learn from it, modify it, and create your own version.
