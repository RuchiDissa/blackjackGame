# 🃏 Blackjack Game

A simple and interactive **Blackjack game built with HTML, CSS, and JavaScript**. This project was created to practice JavaScript fundamentals such as variables, functions, arrays, objects, loops, conditional statements, random numbers, and DOM manipulation.

## 🎮 Features

* Start a new Blackjack game
* Generate random playing cards
* Calculate the current card total
* Add new cards during the game
* Detect Blackjack when the total reaches 21
* Detect when the player goes over 21
* Display the player's name and available chips
* Interactive buttons for starting and continuing the game
* Responsive visual layout with a casino-style background

## 🛠️ Technologies Used

* **HTML5** — Page structure
* **CSS3** — Styling and layout
* **JavaScript** — Game logic and DOM manipulation

## 📂 Project Structure

```text
Blackjack/
│
├── index.html
├── styles.css
├── script.js
└── images/
    └── table.jpg
```

## 🧠 JavaScript Concepts Practiced

This project helped me practice:

* Variables with `let`
* Arrays
* Objects
* Functions
* `if / else if / else`
* `for` loops
* Random number generation with `Math.random()`
* `Math.floor()`
* Array methods such as `push()`
* DOM manipulation
* `getElementById()`
* `querySelector()`
* `textContent`
* Button `onclick` events

## 🃏 How the Game Works

When **Start Game** is clicked, the game generates two random cards.

The cards are stored inside an array:

```javascript
cards = [firstCard, secondCard]
```

The total is then calculated:

```javascript
sum = firstCard + secondCard
```

The game checks the total:

| Total    | Result                       |
| -------- | ---------------------------- |
| Below 21 | Player can draw another card |
| 21       | Blackjack                    |
| Above 21 | Player is out of the game    |

When **New Card** is clicked, another random card is generated and added to the player's cards.

## 🎯 Project Purpose

The main purpose of this project is to strengthen my understanding of **JavaScript fundamentals and interactive web development** by building a small game from scratch.

## 🚀 Future Improvements

Possible future improvements include:

* Add a proper **Reset Game** button
* Add dealer functionality
* Add betting/chip functionality
* Add win/loss tracking
* Add card images instead of displaying numbers
* Add Ace handling for different Blackjack situations
* Improve the game interface and animations
* Add sound effects
* Make the game fully responsive for mobile devices

## 👨‍💻 Author

**Ruchira Dissanayaka**

Computer Engineering Graduate
Interested in Software Engineering, AI/ML, Full-Stack Development, and Mobile Applications.

### 🔗 Connect With Me

* GitHub: https://github.com/RuchiDissa
* Portfolio: https://ruchidissa.github.io/ruchira-dissanayaka.github.io/

---

⭐ If you find this project useful, feel free to explore the code and follow my development journey!
