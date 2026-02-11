# 🔐 Code-Breaker

## 👋 Welcome

Hello! Welcome to the Code-Breaker repository.

## 📖 Description

This program is a version of the popular board game known as MasterMind. It has both the option for the user to play, or play with their own code and allow the code's algorithm to guess.

### ✨ Features

- 🎮 **Interactive Gameplay** - Play the classic MasterMind game
- 🤖 **AI Mode** - Let the computer guess your secret code
- 🎯 **Multiple Difficulty Levels** - Easy, Medium, Hard, and Custom modes
- 🎨 **Colorful GUI** - Visual interface with color-coded feedback
- 🎵 **Sound Effects** - Engaging audio feedback for wins and losses

## 🚀 Getting Started

To get started with Code-Breaker:

1. ☕ Ensure you have Java installed on your system
2. 📥 Clone this repository to your local machine
3. 🔨 Compile the Java source files
4. ▶️ Run the CodeBreaker program to start playing

## 📦 Installation

```bash
# Clone the repository
git clone <repository-url>

# Navigate to the directory
cd Code-Breaker

# Compile the Java file
javac CodeBreaker.java

# Run the program
java CodeBreaker
```

## 🎲 How to Play

### 🎯 Player Mode (Guess the Code)
- The AI generates a secret code using colors: 🟢 Green, 🟣 Purple, 🟡 Yellow, 🟠 Orange, 🔵 Blue, 🔴 Red
- Make your guess and receive feedback:
  - ⚫ **Black** - Right color, right position
  - ⚪ **White** - Right color, wrong position
  - ⚪ **Gray** - Color not in code
- You have 10 attempts to crack the code!

### 🤖 AI Mode (Let the Computer Guess)
- Think of a secret code in your mind
- The AI will make guesses
- Provide feedback using B (Black), W (White), or leave blank for no match
- Watch as the AI narrows down the possibilities!

## 🛠️ Technologies Used

- ☕ Java
- 🖼️ Java Swing (GUI)
- 🎵 Java Sound API

## 📁 Project Structure

- `CodeBreaker.java` - Main game implementation
- `matrix.txt` - Game data file
- `win.wav` - Victory sound effect
- `loss.wav` - Loss sound effect

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs
- 💡 Suggest new features
- 🔧 Submit pull requests

## 📝 License

This project is available for educational and personal use.

## 📞 Contact

For more detailed instructions, please refer to the documentation or contact the repository maintainers.

---

🎮 **Enjoy playing Code-Breaker!** 🎉
