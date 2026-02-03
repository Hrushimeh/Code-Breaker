# Code-Breaker

## Welcome! 👋

Hello and welcome to the Code-Breaker repository! We're glad you're here.

## Description

This program is a version of the popular board game known as MasterMind. It has both the option for the user to play, or play with their own code and allow the code's algorithm to guess. The game features a graphical user interface (GUI) built with Java Swing and includes two exciting modes:

- **Player Mode**: Test your logic skills by guessing the AI's secret code
- **AI Mode**: Watch the computer use algorithms to crack your secret code

## Features

- Interactive GUI with visual feedback
- Multiple difficulty levels (Easy, Medium, Hard, Custom)
- Customizable code length
- Sound effects for win/loss scenarios
- Intelligent AI algorithm that learns from feedback

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Java Runtime Environment (JRE)

### How to Run

1. Compile the Java source file:
   ```bash
   javac CodeBreaker.java
   ```

2. Run the program:
   ```bash
   java CodeBreaker
   ```

3. Choose your game mode:
   - Click "Guess" to play against the AI
   - Click "AI Guess" to let the AI guess your code

### Game Rules

- Available colors: Green (G), Purple (P), Yellow (Y), Orange (O), Blue (B), Red (R)
- **Black feedback**: Right color in the right position
- **White feedback**: Right color in the wrong position
- **Gray feedback**: Color not in the code
- You have up to 10 attempts to crack the code

## Files

- `CodeBreaker.java` - Main game implementation
- `matrix.txt` - Configuration data
- `win.wav` - Victory sound effect
- `loss.wav` - Defeat sound effect

---

*Last Updated: 2024*
