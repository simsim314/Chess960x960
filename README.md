# Chess960x960

**Chess960x960** is an innovative chess variant exploration tool, allowing you to analyze random asymmetric Chess960 positions using Stockfish.

This variant combines two different Fischer Random setups, creating unique and challenging asymmetrical positions.

## Getting Started

Upon loading the page, you'll see the status next to the title:

- **✔ (green check)**: Stockfish has loaded successfully and is ready.
- **X (red)**: Stockfish failed to load. Refresh the page or check your connection.

## UI Overview

### 1. **New Position Button**

- Click **New Position** to load a random Chess960 position.
- The chessboard will update automatically.

### 2. **Evaluation Display**

- After loading a position, Stockfish evaluates it at the chosen depth.
- The evaluation is displayed clearly, in terms of pawns.

### 3. **Depth Selection**

- Adjust the evaluation depth with the **+** or **-** buttons.
- Higher depth takes more time but provides more accurate evaluations.

### 4. **FEN Display & Copy**

- The current position's FEN (a unique chess position code) is displayed below the chessboard.
- Click **Copy** to copy the FEN to your clipboard. The box will briefly turn green to confirm copying.

### 5. **Search by Evaluation Range**

- Click any of the evaluation-range buttons below the FEN to automatically find positions matching that evaluation:
  - **-+** (Decisive advantage for Black)
  - **∓** (Clear advantage for Black)
  - **⩱** (Slight advantage for Black)
  - **=** (Equal)
  - **⩲** (Slight advantage for White)
  - **±** (Clear advantage for White)
  - **+−** (Decisive advantage for White)
- Click **Stop Search** if you'd like to halt the search.

## Tips

- Use depth settings carefully to balance between speed and accuracy.
- The evaluation score represents how favorable the position is (+ means good for White, - means good for Black).

Enjoy exploring Chess960x960!

