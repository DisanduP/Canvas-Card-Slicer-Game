# Canvas Card Slicer Game

A fast-paced, addictive card-slicing game built with HTML5 Canvas. Slice flying cards with precision to rack up points and combos before time runs out!

![Game Screenshot](Screenshot%202026-04-13%20132256.png)

## 🎮 How to Play

- **Aim**: Move your mouse to position the cursor and aim at the incoming cards.
- **Slice**: Click to create a slicing trail that cuts through cards.
- **Score**: Earn points for each card sliced. Build combos by slicing multiple cards in succession for bonus multipliers.
- **Time Limit**: You have 1.5 minutes to achieve the highest score possible!

Cards fly in from the left, right, or both sides simultaneously. Use strategy and reflexes to maximize your combo streak!

## ✨ Features

- **Dynamic Gameplay**: Cards spawn in waves from different directions with randomized timing.
- **Combo System**: Chain slices together for exponentially increasing scores.
- **Smooth Animations**: Fluid cursor trails and card slicing effects powered by custom sprites.
- **Responsive Design**: Adapts to different screen sizes with proper scaling.
- **Particle Effects**: Engaging visual feedback with gravity and physics simulation.
- **Time Pressure**: Race against the clock for high-score challenges.

## 🚀 Getting Started

### Prerequisites
- A modern web browser with JavaScript enabled (Chrome, Firefox, Safari, Edge).

### Running the Game
1. Clone or download this repository.
2. Open `index.html` in your web browser.
3. Click "Start" to begin playing!

No installation required – it's a pure client-side web game.

## 🛠️ Technologies Used

- **HTML5 Canvas**: For rendering the game graphics and handling user input.
- **JavaScript (ES6)**: Game logic, physics, collision detection, and animation.
- **SAT.js**: Collision detection library for precise polygon and point interactions.
- **Meowgine**: Custom game engine for sprites, particles, and surface management.
- **CSS3**: Styling for overlays, buttons, and responsive layout.
- **Google Fonts**: Quicksand and Rubik Glitch for a sleek, retro gaming aesthetic.

## 📝 Game Mechanics

- **Cursor Trail**: Your slicing tool leaves a visual trail that persists briefly for collision detection.
- **Card Physics**: Cards rotate and fall with gravity, friction, and random initial velocities.
- **Scoring System**: Base points per card (1) multiplied by combo count. Combos reset on miss.
- **Wave Spawning**: Random intervals between 1-2 seconds, with weighted chances for left/right/both directions.
- **End Game**: Timer counts down from 1:30. Game over displays final score with restart option.

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements, bug fixes, or new features. Ideas welcome!

## 📄 License

This project is open source. If you'd like to use it commercially or modify it extensively, please consider adding a license (e.g., MIT) to the repository.

Enjoy slicing those cards! 🃏✂️