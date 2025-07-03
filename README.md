# 📝 TEL — Terminal-Based Text Editor for Linux

**TEL** (Text Editor for Linux) is a minimalist terminal-based text editor written in pure C. It features line numbering, highlighted cursor line, and smooth navigation — all in under 600 lines of code.

![TEL Demo](demo.gif) <!-- Replace with your own screenshot or GIF -->

---

## 📌 Features

- 🔢 **Line Numbers** — every row starts with its line number
- 🎯 **Active Line Highlighting** — the line under the cursor is visually distinct
- 📄 **File Editing** — open, edit, and save plain text files
- ⌨️ **Basic Keyboard Controls** — arrow key navigation, save & quit shortcuts
- 📜 **Minimalist Interface** — clean, distraction-free terminal UI
- ⚙️ **Raw Mode Input** — character-by-character input handling using `termios`

---

## 🛠️ Tech Stack

| Language | OS / Terminal | Libraries / APIs |
|----------|---------------|------------------|
| C (C99)  | Linux (Ubuntu) | `termios.h`, ANSI Escape Codes |

---

## 📂 Project Structure
├── tel.c # Source code
├── Makefile # Build script
├── README.md
└── test.txt # Sample input file


---

## ⚙️ Installation & Running

### 🔧 Compile

```bash
git clone https://github.com/AkhileshPatidar04/tel-text-editor.git
cd tel-text-editor
gcc tel.c -o tel -std=c99


## Acknowledgements
Inspired by Kilo by Salvatore Sanfilippo (@antirez)

Built using Unix terminal raw mode + ANSI control codes
