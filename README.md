# KSPCR

KSPCR is a fantasy computer. The instructions are below and sample TXT project demos will be in the repository.

## 📋 Instruction Set

Each instruction in a TXT file is **separated by a backslash** (`\`).

| Code | Instruction | Description |
|------|-------------|-------------|
| 1 | Set I | Sets the value of the I register |
| 2 | Replace RAM | Replaces a value in RAM |
| 3 | Go to X | Sets the X position |
| 4 | Go to Y | Sets the Y position |
| 5 | Draw | Draws a part of RAM at the X and Y position |
| 6 | Jump to Line | Jumps to a specified line |
| 7 | Conditional Jump | Jumps to line (item 1 of RAM) if a specified section of RAM equals I |
| 8 | Add | Adds a specified number and I together |
| 9 | Halt | Stops all execution (STOP ALL) |
| 10 | Get Key | Gets the key the user is currently pressing |
| 11 | Clear Screen | Clears the screen |

## 🎮 Getting Started

1. Create a new `.txt` file for your project
2. Write instructions using the codes above
3. **Separate each instruction with a backslash** (`\`)
4. Execute your project in KSPCR

### Example:
```
11/\3/-79\4/44\5/1
```

## 📚 Sample Projects

Check the repository for sample TXT project demos to learn more!

---

**KSPCR** - A fantasy computer for creative coding
