# Collatz Visualizer

This is a small desktop app that visualizes the Collatz Conjecture. The math rule is pretty simple: if a number is even, you divide it by 2. If it's odd, you multiply it by 3 and add 1. This app takes a number you type in, and then calculates and draws the paths for all numbers from 1 up to that number to see how they behave.

## Why I made this
I built this project mostly as personal practice while I'm learning Python. I recently found out about the Collatz Conjecture and thought it was really interesting, so I figured I would try to build something around it to see the patterns for myself.

## Important Note
This program is not meant for massive calculations. If you put in a really high number, the graph is going to get pretty crowded and might slow down a bit. But it still does a good job of showing how the sequences swing wildly up and down before every single one drops down to 1 eventually.

## Features
- Fully GUI based (no terminal needed)
- Generates all sequences from 1 up to N at the same time
- Graph is embedded right inside the application window
- Clean and simple interface

## How to run it
Make sure you have Python installed. You'll also need to install the extra libraries before running it:

```bash
pip install customtkinter matplotlib
```

Then just run the main file:

```bash
python app.py
```


