# "I made a Breakthrough" - Breakthrough Chess-Variant Game
*Author:* Michael R. Martin
*Current version: 0.9*

A fast-paced, strategy game inspired by the "Breakthrough" chess-variant board game. 
This project highlights innovative AI implementation, minimalist creative design, and technical depth, showcasing skills in game development and computational media.

---

## Gameplay Video
https://github.com/user-attachments/assets/2ff4e38c-81b8-437c-a220-4153685affd6

---


## Game Overview

**Genre**: Strategy (Turn-Based/Abstract Strategy)  
Breakthrough challenges players to outmaneuver their opponent's pawns and reach the board’s back row. The game features two modes:
- **Classic Mode**: Deliberative gameplay with no time limits.
- **War Mode**: Main game mode; Fast-paced gameplay with timed turns and an AI opponent with consistent adaptation.

Players can compete against a dynamic AI opponent or another human player.

---

## How to Play

1. **Objective**: Advance your pawns to the opponent's back row while blocking their progress.
2. **Controls**:
   - Click to select a pawn and choose its movement (forward, diagonal-left, or diagonal-right).
   - In War Mode, make decisions quickly within given time constraint.
3. **AI Gameplay**:
   - Adjust difficulty through game settings for learning the basics or competitive gameplay.

---

## Key Features

### Technical Highlights
1. **Minimax Algorithm**:
   - Implements a robust AI system for decision-making.
   - Evaluates potential moves (forward, diagonal-left, diagonal-right) based on board state and prioritizes strategic actions, such as attacking or advancing.
   - Adaptive depth for challenging gameplay.
2. **Dynamic Game Logic**:
   - Efficient board management and piece interactions.
   - Asynchronous AI calculations for ideal transitions between turns.
   - Interactive move highlights and attack animations.
3. **Sound & Effects**:
   - Custom-coded sound management integrated with the Unity engine.

### Creative Contributions
- **Art & Animation**:
  - Minimalist pixel-art style designed for clarity and engagement.
  - Fluid animations for pawn movement and interactions, leveraging Unity's tweening capabilities.
- **Music & Sound**:
  - Original background music composed in a retro synth style.
  - Dynamic sound effects, such as destruction, movement, and victory, enhance the player experience.
  - Custom sound engine integrated into the gameplay for reactive audio transitions.

### Interpretive Aspects
- Designed with player behavior and decision-making in mind; AI adapts playstyle to challenge users effectively.
- Explores themes of competition and adaptability in strategic environments.

---

## Development Details

### Technical Systems
1. **AI Opponent**:
   - The AI leverages a Minimax algorithm with custom scoring to evaluate board states and choose optimal moves.
   - Depth-based evaluation adjusts to difficulty.
2. **Game Logic**:
   - Manages board initialization, piece spawning, and movement logic, ensuring smooth gameplay transitions.
   - Dynamic board state evaluation tracks progress and enforces game rules.
3. **Sound Integration**:
   - Original sound effects and music dynamically interact with game states for an immersive experience.
   - Includes sound selection based on triggers (e.g., attacks, turns, victories).

### Tools & Frameworks
- **Language**: C#  
- **Engine**: Unity  
---
## Development Timeline:
  - Alpha (9/27/2023): Core board and movement implementation.
  - Beta (10/4/2023): AI implementation and testing for "Classic Mode."
  - Final (10/11/2023): Added "War Mode," finalized art and sound design, and fixed gameplay bugs from beta build.
---
## License
## All rights reserved. This code is proprietary and may not be copied, distributed, or used without explicit permission from the owner.
