# CoinHit

A gameplay-focused Unreal Engine prototype built around player-versus-AI competition, resource collection, and replayability.

CoinHit began as part of an Unreal Engine workshop that introduced foundational systems such as character movement, UI implementation, AI navigation, and coin collection. I then expanded the project by designing and implementing a competitive player-versus-AI gameplay loop focused on replayability and resource competition.

---

## Project Status

**Current Status:** Playable Prototype

The project serves as an exploration of gameplay systems, AI competition, player decision-making, and replayability within Unreal Engine using Blueprints.

---

## Gameplay Overview

The player competes against an AI-controlled opponent to collect as many coins as possible before all available coins on the map are exhausted.

Both the player and AI continuously accumulate points based on collected coins, creating a competitive race for resources.

The match ends once all coins have been collected, after which the final scores are displayed on the end screen.

---

## Gameplay Showcase
<img width="1024" height="607" alt="Untitleddesign9-ezgif com-optimize" src="https://github.com/user-attachments/assets/e86a2538-c90a-4c26-bee3-04f0b298d022" />
<img width="1024" height="607" alt="Untitleddesign10-ezgif com-optimize" src="https://github.com/user-attachments/assets/31f7b9a9-c194-4f93-8de5-3e64a126741a" />

<img width="1024" height="607" alt="Untitleddesign8-ezgif com-optimize" src="https://github.com/user-attachments/assets/db3309fd-6269-484b-bba1-6882e70948b8" />

---

## My Contribution

Building upon the workshop foundation, I independently designed and implemented:

- Competitive player-versus-AI gameplay loop
- Score tracking and comparison system
- Win/loss gameplay structure
- Dual coin-type gameplay mechanic
- Resource competition design
- Gameplay balancing and testing
- Project integration and iteration

---

## Original Design Contributions

The workshop provided foundational Unreal Engine systems and tooling. My primary contribution was transforming those systems into a complete gameplay experience through:

- Competitive player-versus-AI gameplay
- Dual coin risk/reward mechanics
- Score race structure
- Match progression and end conditions
- Replayability-focused balancing

---

## Core Features

- Custom third-person character controller
- Animation Blueprint integration
- Enhanced Input System setup
- AI opponent navigation system
- Live player and AI score tracking
- Start menu UI
- End screen UI
- Multiple coin types
- Replayability-focused gameplay loop

---

## Gameplay Systems

### Competitive Resource Collection

The core gameplay revolves around competing against an AI opponent for a limited number of resources.

Players must balance movement efficiency, route planning, and coin prioritization to outperform the AI before all resources are depleted.

---

### Dual Coin System

The project features two collectible coin types:

#### Yellow Coins

- Increase player score
- No gameplay penalty

#### Red Coins

- Increase player score
- Temporarily reduce player movement speed

This creates a simple risk-versus-reward decision where players must choose whether additional points are worth sacrificing mobility.

---

### AI Opponent

The AI continuously searches for and moves toward the nearest available coin.

Using Unreal Engine's navigation system, the AI dynamically updates its target as coins are collected, creating an active competitor rather than a static obstacle.

The AI's presence creates:

- Resource pressure
- Route optimization decisions
- Replayability through competition

---

### Score Tracking System

The game tracks:

- Player score
- AI score
- Current match state

Scores update in real time throughout the match, allowing players to continuously evaluate their performance relative to the AI opponent.

---

### UI Systems

The project includes:

#### Start Screen

- Game introduction
- Match start flow

#### Gameplay HUD

- Live score display
- Match information

#### End Screen

- Final score comparison
- Match result presentation

---

## Technical Focus

This project was created to explore:

- Unreal Engine Blueprints
- Gameplay prototyping
- AI navigation systems
- Character controller implementation
- UI systems
- Gameplay loop design
- Replayability through competition

---

## Challenges Solved

### Creating Meaningful AI Competition

Instead of treating the AI as an enemy, the project frames it as a competing resource collector. This creates tension through competition rather than combat.

### Risk-Reward Decision Making

Introducing red coins allowed players to gain additional points while sacrificing movement speed, creating simple but meaningful choices.

### Replayability

Because both the player and AI compete for shared resources, different matches can play out differently depending on movement decisions and collection routes.

---

## Tech Stack

- Unreal Engine 5
- Blueprints
- Animation Blueprints
- Enhanced Input System
- Unreal Navigation System

---

## Key Takeaways

Through this project I gained experience with:

- Gameplay prototyping in Unreal Engine
- Blueprint scripting
- AI navigation systems
- UI implementation
- Character controller setup
- Gameplay balancing
- Competitive gameplay design
- Rapid iteration workflows

---

## Future Improvements

Planned future improvements:

- Smarter AI decision-making
- Multiple AI difficulty levels
- Additional power-ups
- Larger maps
- Dynamic coin spawning
- Time attack mode

---

## Developer

Mohd Ayaan Khan

GitHub:
https://github.com/MAK031205

itch.io:
https://mohdayaankhan.itch.io

ArtStation:
https://mak031205.artstation.com
