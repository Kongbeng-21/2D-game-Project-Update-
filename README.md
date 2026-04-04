# 🎮 2D Side-Scroller Game (Unity)

## 📌 Overview
This project is a 2D side-scrolling game developed in Unity, focusing on character control, enemy behavior, and interactive game systems.

The goal of this project is to build a complete gameplay system with smooth movement, responsive interaction, and modular design.

---

## 🚀 Features
- Player movement with goal-based navigation
- Enemy/character behavior using state-based logic (IDLE / MOVE)
- Interactive click-to-move system using raycasting
- Dynamic animation system with runtime UI controls
- Moving platforms with velocity transfer
- Elevator system with smooth motion using second-order dynamics

---

## 🧠 System Design Highlights

### 🎯 State-Based Character Control
- Implemented a state machine (IDLE, MOVE)
- Handles movement using direction vectors and distance checks
- Ensures smooth transitions between actions

### 🖱️ Input & Interaction System
- Used raycasting to detect player clicks
- Dynamically assign movement targets
- Built UI panel to control animations in real-time

### ⚙️ Physics & Platform System
- Moving platforms transfer velocity to player objects
- Elevator system uses second-order dynamics for realistic motion

---

## Challenges

### 1. Movement & Collision Bugs
- Issue: inconsistent movement and jitter
- Solution: refactored movement logic and normalized direction vectors

### 2. Animation Control Complexity
- Issue: managing multiple animation states dynamically
- Solution: built animation panel system to control states at runtime

---

## What I Learned
- Object-oriented design in game systems
- Physics-based movement and interaction
- State machine implementation for character behavior
- Debugging complex gameplay systems

---

## Future Improvements
- AI-driven enemy behavior (adaptive difficulty)
- Player behavior analysis for dynamic gameplay tuning
- Pathfinding system (A* or navigation mesh)
