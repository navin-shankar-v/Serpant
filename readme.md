# 🐍 Sssserpent Struggle

A modern twist on the classic Snake game, featuring AI-powered enemy snakes that compete for food!

> **Created by NavinShankar**

---

## 🎮 About the Game

**Sssserpent Struggle** is a reimagined version of the timeless Snake game. Navigate your snake across the playing field, consume pellets to grow longer, but beware—you're not alone!

Enemy snakes powered by a **greedy path-finding algorithm** are hunting the same food. Outsmart them, outmaneuver them, and survive as long as you can!

### Collision Rules

- **Body collision:** If a snake hits another's body, it loses length from the collision point
- **Head-on collision:** The shorter snake is eliminated—if that's you, it's game over!

---

## ⚡ Key Features

- 🎨 Clean, nostalgic visual design
- 🕹️ Smooth and responsive controls
- 📈 Progressive difficulty as your snake grows
- 🤖 Four AI enemy snakes with intelligent path-finding
- 🧱 Strategic obstacles that require careful navigation

---

## 🔧 Installation

### Prerequisites

- Python 3.x
- Pygame library

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/NavinShankar/Sssserpent-Struggle.git
   cd Sssserpent-Struggle
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the game:**
   ```bash
   python snake.py
   ```

---

## 🎯 How to Play

- Use **Arrow Keys** to control your snake's direction
- Eat pellets to grow longer and increase your score
- Avoid colliding with walls, obstacles, and enemy snakes
- After a set time, four enemy snakes will join the field—stay sharp!

---

## 🛠️ Built With

- **Python** - Core programming language
- **Pygame** - Game development library
- **Greedy Algorithm** - Enemy snake AI path-finding

---

## 🚧 Development Challenges

Building the greedy path-finding algorithm for enemy snakes was the most challenging aspect. The AI needed to be efficient and intelligent enough to compete effectively for pellets while maintaining smooth gameplay performance.

---

## 🚀 Future Roadmap

- [ ] New game modes and challenges
- [ ] Multiplayer support
- [ ] Global leaderboard system
- [ ] Customizable snake skins and themes

---

## 📄 License

This project is licensed under the terms included in the [LICENSE](LICENSE) file.

---

**Enjoy the game! 🐍✨**
