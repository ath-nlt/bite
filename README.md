# Bite

Bite is a minimal, terminal-based text editor written in C. It's designed to be simple, lightweight, and easy to understand. It doesn't have many bells and whistles, but it gets the job done for quick edits.

## Features

- **Lightweight**: Written in pure C with minimal dependencies.
- **Clean UI**: Simple header and footer to keep you focused.
- **Basic Editing**: Supports inserting text, newlines, and backspacing.
- **Navigation**: Use your arrow keys to move around naturally.

## Getting Started

### Prerequisites

You'll need a C compiler (like `gcc`) and a terminal that supports ANSI escape codes.

### Build and Run

1. Clone the repository (if you haven't already).
2. Compile the source code:
   ```bash
   gcc main.c -o bite
   ```
3. Run the editor:
   ```bash
   ./bite
   ```

## Controls

- **Arrow Keys**: Move the cursor around the screen.
- **Enter**: Start a new line.
- **Backspace**: Delete characters.
- **Esc + w**: Save your work to `untitled.txt` and exit.
- **Ctrl + C**: Force quit (unsaved changes will be lost).

## Why "Bite"?

The name stands for bite is a text editor.

## License

This project is open-source. Feel free to use, modify, and share it.
