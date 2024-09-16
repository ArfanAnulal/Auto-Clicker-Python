# Automated Mouse Clicker Script

## Overview

This script is a simple automation tool that uses the `pyautogui` library to simulate continuous mouse clicks with a short delay between each click. It is useful for applications that require repetitive mouse clicking, such as testing, games, or other automated tasks. 

## Features
- Automates mouse clicks using the `pyautogui` library.
- Repeats the mouse click indefinitely with a short delay of 0.1 seconds between each click.

## Prerequisites

Before running the script, ensure that you have the following installed:

1. **Python 3.x** - Make sure Python is installed on your system. You can download it from the [official Python website](https://www.python.org/downloads/).
2. **pyautogui library** - This library is used for automating mouse and keyboard functions.

### Installing `pyautogui`
You can install the `pyautogui` library via pip:
  ```bash
  pip install pyautogui

```
## How the Script Works

1. **Importing Libraries**: The script imports `pyautogui` for mouse automation and `time` to control the delay between each mouse click.

2. **Infinite Loop**: The script runs an infinite loop (`while True:`) to continuously click the mouse.

3. **Mouse Clicks**: The `pyautogui.click()` function simulates a mouse click at the current cursor location.

4. **Sleep Interval**: After each click, the script pauses for 0.1 seconds (`time.sleep(0.1)`) before the next click.

## How to Use the Script

1. **Run the Script**: To execute the script, run it in your Python environment:
   ```bash
   python auto_clicker.py
2. **Stop the Script**: Since the script runs indefinitely, you will need to manually stop it by pressing `Ctrl + C` in the terminal.

## Customization

You can modify the delay between clicks or add more functionality to the script based on your needs. For example:

- **Change the Delay**: You can adjust the `time.sleep(0.1)` to a different value for faster or slower clicking.
  
  ```python
  time.sleep(0.5)  # Slows down clicking to once every 0.5 seconds

- **Click at Specific Coordinates**: You can make the script click at specific coordinates on the screen by using pyautogui.click(x, y) where x and y are the pixel coordinates.
  ```python
  pyautogui.click(100, 200)  # Clicks at position (100, 200)
## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
