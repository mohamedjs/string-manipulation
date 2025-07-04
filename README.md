# String Manipulation – C & MIPS Assembly

A collection of string manipulation utilities implemented in both C and MIPS Assembly. The project provides a menu-driven interface for analyzing and transforming text, including character and word statistics, search/replace, frequency analysis, and sorting.

---

## 🧩 Features

- **Character Statistics & Frequency:** Count and display the frequency of each character in a paragraph.
- **Word Statistics:** Count and display the frequency of each word in a paragraph.
- **Find and Replace:** Search for a word or character and replace it with another.
- **Frequency Filter:** List all characters or words that appear exactly once, twice, or three times.
- **Search Occurrences:** Count the number of times a specific word or character appears.
- **Quicksort:** Sort all words in the paragraph alphabetically using quicksort.
- **Menu-Driven:** Interactive menu for selecting operations.
- **Implemented in Both C and MIPS Assembly:** Compare logic and performance between high-level and low-level implementations.

---

## 📁 Files

- `string-manipulation.c` – Main C implementation with all features and menu.
- `string_manipulation.asm` – MIPS Assembly implementation with equivalent features and menu.

---

## 🚀 How to Run

### C Version
1. **Compile:**
   ```bash
   gcc string-manipulation.c -o string-manipulation
   ```
2. **Run:**
   ```bash
   ./string-manipulation
   ```
3. **Follow the menu prompts to enter a paragraph and select operations.**

### MIPS Assembly Version
1. **Open in a MIPS simulator** (e.g., MARS or SPIM).
2. **Assemble and run** `string_manipulation.asm`.
3. **Follow the menu prompts in the console.**

---

## 📝 Menu Options

1. **Character Statistics, Frequency**
2. **Word Statistics**
3. **Find and Replace a Character or Word**
4. **Get All Characters/Words with Frequencies of 1, 2, or 3**
5. **Search for a Specific Word/Character**
6. **Sort Words Using Quicksort**
0. **End the Program**

---

## 🛠️ Code Overview

### C Implementation (`string-manipulation.c`)
- Uses standard C libraries for string handling.
- Functions for each menu operation (character/word frequency, search/replace, quicksort, etc).
- Menu-driven loop for user interaction.

### MIPS Assembly Implementation (`string_manipulation.asm`)
- Equivalent logic to the C version, implemented in MIPS assembly.
- Uses system calls for I/O and manual memory management.
- Implements string parsing, comparison, sorting, and statistics at the register level.

---

## 👤 Author
- Educational project for learning and comparing string manipulation in C and Assembly.

---

Enjoy exploring string manipulation at both high and low levels! 