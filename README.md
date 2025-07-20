# 🔧 Truss Analysis Tool — Group 05 (ES221 Project)

## 📚 Overview

This project presents a **computational tool for analyzing 2D truss systems**, developed as part of the **ES221: Mechanics of Solids** course at IITGN. The solver, built using **Wolfram Mathematica**, calculates internal member forces and visualizes the results using color-coded truss diagrams.

## 👨‍🔬 Team Members

- Anuj Manoj Joshi (23110033)  
- Chaudhari Sarvesh Pravin (23110076)  
- Jatin Agarwal (23110147)  
- Tanushka Anand Sonde (23110332)  
- Yug Mitulkumar Desai (23110370)

## 🏗️ Problem Statement

Analyze a statically determinate fixed truss system under user-defined loads. Determine:

- Support reactions  
- Internal axial forces (Tension/Compression)  
- Visual representation of the truss force distribution

## 🎯 Objectives

- Implement truss analysis using:
  - Static Equilibrium
  - Method of Joints
- Allow custom user input for loads
- Automate the classification of forces (tension/compression)
- Generate a graphical output with clear labeling and force magnitudes

## 🛠️ Methodology

1. **Truss Definition**: Nodes and members are pre-defined for a specific geometry to ensure accuracy.
2. **User Input**: Users enter loads at selected nodes in a simple format.
3. **Equilibrium Analysis**:
   - Support reactions computed using ΣFₓ=0, ΣFᵧ=0, ΣM=0
   - Internal forces determined using Method of Joints
4. **Force Classification**:
   - Red: Tension  
   - Green: Compression  
   - Black: Near-zero force
5. **Visualization**: Final output includes an annotated truss diagram with force values and directions.

## 💻 Files Included

| File | Description |
|------|-------------|
| `Truss_Solver.nb` | Mathematica notebook containing the full solver code |
| `Group_05_ES221_Project_Report.pdf` | Full technical report detailing the methodology, assumptions, results, and discussion |
| `MOS_GROUP-05.pdf` | Presentation summary of the project with key visuals and results |

## 📈 Results Snapshot

Example member force results (kN):

| Member | Force | Type |
|--------|-------|------|
| FAB    | 60.0  | Tension |
| FGH    | 94.87 | Compression |
| FDE    | 90.0  | Tension |

Visualization includes support reactions, member labeling, and a color-coded diagram.

## ✅ Outcomes

- Verified results using both hand calculations and symbolic solutions.
- Developed a user-interactive tool for educational and analytical purposes.
- Gained hands-on experience in structural analysis and software implementation.

## 📎 References

- [Mathalino – Truss by Method of Joints](https://mathalino.com/reviewer/engineering-mechanics/problem-414-truss-method-joints)
