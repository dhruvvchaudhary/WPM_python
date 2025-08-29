# ⌨️ Speed Typing Test (Python + Curses)

A simple **terminal-based Speed Typing Test** built using Python’s `curses` library.  
It measures your **Words Per Minute (WPM)** while you type random sentences from a text file.

---

## 📌 Features
- Displays random sentences from `text.txt`  
- ⏱Real-time **WPM calculation**  
- Correct characters highlighted in **green**  
- Incorrect characters highlighted in **red**  
- Backspace support  
- Press **ESC** to quit anytime  
- Restart after completion  

---

## 📂 Project Structure
    speed_typing_test/
    │── text.txt              # Sentences for typing
    │── tutorial.py               # Main Python script
    │── README.md             # Project documentation

---

## ⚙️ Requirements
- Python **3.7+**
- Works on:
  - Linux terminal  
  - macOS terminal  
  - Windows Terminal (with curses support)

---

## 🚀 How to Run
1) Clone this repository or download the files.

    git clone https://github.com/yourusername/speed-typing-test.git
    cd speed-typing-test

2) Ensure `text.txt` exists next to `tutorial.py`. Example `text.txt`:

    Typing speed is an essential skill in the modern world..
    Python makes programming fun and powerful.
    Typing fast improves your productivity.

3) Run the program:

    python tutorial.py

---

## 🎮 Controls
| Key        | Action                           |
|------------|----------------------------------|
| **Type**   | Type the sentence shown          |
| **Backspace** | Delete last character        |
| **ESC**    | Exit the test anytime            |
| **Any key**| Start a new round after finishing|

---

## 🖼️ Demo (Concept)
    Welcome to the Speed Typing Test!
    Press any key to begin!

    Typing speed is an essential skill in the modern world.
    WPM: 42
    The quik ▒

---

## 🛠️ Customization
- Add/remove sentences in `text.txt` for different practice texts.  
- Change colors in `main()`:

    curses.init_pair(1, curses.COLOR_GREEN, curses.COLOR_BLACK)  # Correct char
    curses.init_pair(2, curses.COLOR_RED, curses.COLOR_BLACK)    # Wrong char
    curses.init_pair(3, curses.COLOR_WHITE, curses.COLOR_BLACK)  # Default

---

## 📜 License
This project is open-source and available under the **MIT License**.
