# Keyboard Key Detector

A simple JavaScript project that detects the key pressed on the keyboard and displays its **Symbol, Keycode, and Code** dynamically.

## Features

* Detects keyboard key presses using the `keydown` event.
* Displays the pressed key.
* Shows the keycode.
* Shows the JavaScript keyboard code.
* Displays `Space` instead of an empty space when the Spacebar is pressed.

## Technologies Used

* HTML
* CSS
* JavaScript

## How It Works

The project uses JavaScript's `keydown` event to detect keyboard input and updates the webpage with information about the pressed key.

```javascript
window.addEventListener('keydown', (e) => {
    // Displays key information
});
```

## How to Run

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Open the HTML file in a browser.
4. Press any key on the keyboard to see its details.

## Example

When you press the **A** key:

| Symbol | Keycode | Code |
| ------ | ------- | ---- |
| a      | 65      | KeyA |

## Learning Purpose

This project was created to practice:

* JavaScript Events
* `keydown` Event
* DOM Manipulation
* Template Literals
* Keyboard Event Properties
