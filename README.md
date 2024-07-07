# Tic-Tac-Toe iOS App

This project is a simple implementation of the classic Tic-Tac-Toe game for iOS devices, developed using Swift and Xcode.

## Project Structure

- `Tictactoe.xcodeproj/`: The Xcode project file.
- `Tictactoe/`: The main source directory containing the Swift files and resources for the app.

## Getting Started

### Prerequisites

- macOS with the latest version.
- Xcode installed (version 12.0 or higher recommended).

### Installation

1. **Clone the repository:**
   ```sh
   git clone <repository-url>```
   
2. **Navigate to the project directory:**
   ```sh
   cd Tictactoe```
3. **Open the project in Xcode:**
   ```sh
   open Tictactoe.xcodeproj  ```
### Running the App

1. Select the target device (Simulator or physical device) from the top device bar in Xcode.
2. Press the `Run` button (or `Cmd + R`) to build and run the app.

## Features

- **Single Player Mode:** Play against the computer.
- **Two Player Mode:** Play with a friend on the same device.
- **Simple UI:** Easy-to-use interface with clear game board and controls.

## Code Overview

### ViewController.swift

This file contains the main logic for the game, including:

- Initializing the game board.
- Handling player moves.
- Checking for win conditions.
- Updating the UI based on game state.

### Model

The model handles the game state, including the game board and player turns.

### Views

The views display the game board and player controls.
