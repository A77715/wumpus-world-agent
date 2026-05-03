# wumpus-world-agent
AI agent using CNF and resolution
# Wumpus World Logic Agent

A knowledge-based AI agent that solves the classic **Wumpus World problem** using logical reasoning instead of random exploration.

The agent uses **CNF-based knowledge representation** and **resolution inference** to determine safe and dangerous cells in real time.

---

## Project Overview

This project simulates an intelligent agent in a grid-based world where it must:
- Avoid pits and the Wumpus
- Detect percepts (Breeze, Stench, Glitter)
- Reason logically about the environment
- Reach safe cells and collect gold

The system is inspired by the concepts from:
:contentReference[oaicite:0]{index=0}

---

## Key Concepts Used

- Propositional Logic
- CNF (Conjunctive Normal Form)
- Resolution Inference
- Knowledge Base (KB)
- Unit Propagation
- Rule-based reasoning

---

## Features

- Dynamic grid-based world generation  
- Random placement of pits, Wumpus, and gold  
- Real-time percept generation (Breeze, Stench, Glitter)  
- Knowledge base with logical facts  
- Resolution-based inference engine  
- Safe vs dangerous cell detection  
- Step-by-step agent movement  
- Auto-run simulation mode  
- Visual grid UI with status indicators  

---

## How It Works

1. The agent starts at position (0,0)  
2. It perceives environment signals:
   - Breeze → nearby pit  
   - Stench → nearby Wumpus  
   - Glitter → gold found  
3. These percepts are stored in a knowledge base  
4. Logical inference is applied using:
   - CNF-style rules  
   - Resolution technique  
5. Cells are classified as:
   - Safe  
   - Dangerous  
   - Unknown  
6. The agent chooses the safest possible move  

---

## Tech Stack

- HTML  
- CSS  
- JavaScript (Vanilla)

---

## How to Run

1. Download or clone the repository  
2. Open `index.html` in any browser  
3. Use buttons:
   - New World → Generate environment  
   - Step Agent → Move step-by-step  
   - Auto Run → Run automatically  

---

## Project Highlights

- Demonstrates symbolic AI reasoning  
- Implements simplified resolution-based inference  
- Visualizes decision-making process in real time  
- Educational simulation of intelligent agents  

---

## Learning Outcome

This project helped in understanding:
- How AI agents reason logically  
- How knowledge bases are constructed  
- How inference engines derive conclusions  
- Practical use of propositional logic in AI systems  

---

## Author

Your Name  
(Replace with your actual name)

---

## License

This project is for educational purposes.
