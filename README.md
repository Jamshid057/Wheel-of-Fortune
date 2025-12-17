# Pole Chudes (Wheel of Fortune) — C Console Game

## 📌 Description

This project is a **console-based implementation of the classic game "Pole Chudes" (known internationally as "Wheel of Fortune")**, written entirely in **C programming language**.

The player tries to guess a hidden word **letter by letter**. Correct guesses reveal letters in the word, while incorrect guesses reduce the number of attempts. The goal is to guess the full word before running out of attempts.

This project was created as a **learning and practice project** to improve skills in C programming, file handling, loops, conditions, and basic game logic.

---

## 🎮 Game Features

* Console-based interface
* Random word selection from a file
* Letter-by-letter guessing system
* Displays guessed letters and current word state
* Limited number of attempts
* Simple and clear game flow

---

## 🛠 Technologies Used

* **Language:** C
* **Compiler:** GCC (or any standard C compiler)
* **Platform:** Linux / macOS / Windows (console)

---

## 📂 Project Structure

```
Pole-Chudes/
│── main.c            # Main game logic
│── words.txt         # List of words used in the game
│── README.md         # Project documentation
```

---

## ▶️ How to Compile and Run

### 1. Clone the repository

```bash
git clone https://github.com/Jamshid057/Wheel-of-Fortune.git
cd pole-chudes
```

### 2. Compile the program

```bash
gcc main.c -o pole_chudes
```

### 3. Run the game

```bash
./pole_chudes
```

---

## 📄 Words File Format

The `words.txt` file should contain **one word per line**. Example:

```
computer
programming
keyboard
linux
algorithm
```

---

## 📈 Learning Outcomes

This project helped to practice:

* Working with strings in C
* File input/output (`fopen`, `fgets`, `fclose`)
* Loops and conditional logic
* Arrays and character handling
* Building a simple game logic

---

## 🚀 Future Improvements

* Add score system
* Add difficulty levels
* Support full words guessing
* Improve UI (ASCII graphics)
* Add multiplayer mode

---

## 👤 Author

**Jamshid**
Backend Developer | C & Python Learner

---

## 📜 License

This project is open-source and free to use for educational purposes.
