### 📝 TEL — Terminal-Based Text Editor for Linux

**TEL** (Text Editor for Linux) is a minimalist terminal-based text editor built from scratch in pure C. It provides essential editing features such as line numbering, active line highlighting, and file saving — all implemented using low-level terminal control and ANSI escape codes. TEL is inspired by the philosophy of simplicity and full control, much like `vim` or `nano`, but without external dependencies.

![TEL Demo](demo.gif) <!-- Replace this with your own screenshot or GIF -->

---

## 📌 Features

- 🔢 **Line Numbers** – Displays line numbers beside each row
- ✨ **Highlighted Cursor Line** – Highlights the currently active line
- 💾 **File I/O** – Open and save plain text files from the terminal
- ⌨️ **Keyboard Navigation** – Use arrow keys, PageUp/PageDown to navigate
- ⚙️ **Raw Mode Input** – Uses `termios` for low-level, character-by-character input handling
- 📟 **Minimal Footprint** – Compact and clean codebase with no third-party libraries (~600 LOC)

---

## 🛠️ Tech Stack

| Language | OS / Terminal | Libraries / APIs |
|----------|---------------|------------------|
| C (C99)  | Linux (Ubuntu) | `termios.h`, ANSI Escape Codes |

---

## 📂 Project Structure
tel/
├── tel.c # Core source code
├── Makefile # Build script
├── README.md # Project documentation
└── test.txt # Sample text file to open/edit
