---
title: Program
nav: true
---

# Workshop Program

{% include figure.html img="EuroGNC_Workshop_Schedule.png" alt="Workshop schedule overview" width="95%" %}

## Pre-Conference Tutorial Workshop  
**Control Barrier Functions in Aerospace: From Foundations to Real-World Applications**

**Date:** May 4, 2026  
**Time:** 07:50–17:30 CEST  
**Location:** Universidad Carlos III de Madrid, Madrid, Spain  
**Format:** Hybrid (in-person & virtual)

---

## Tentative Schedule

- **07:50–08:00** — Welcome & Opening Remarks  

- **08:00–08:45**  
  **Control Barrier Functions: Theory Overview and How to Design Them Using Dynamic Safety Margins**  
  *Victor Freire, Marco Nicotra* — University of Colorado Boulder

- **08:45–09:30**  
  **Scalable Safe Control Design: Recent Advances and Open Challenges**  
  *Kunal Garg* — Arizona State University

- **09:30–09:50** — Coffee Break  

- **09:50–10:35**  
  **Designing Control Barrier Functions with Convex Optimisation**  
  *Han Wang, Kostas Margellos, Antonis Papachristodoulou* — ETH Zurich & University of Oxford

- **10:35–11:20**  
  **Safety-Critical Multi-UAV Cooperative Guidance via Distributed MPC and Control Barrier Functions**  
  *Hyo-Sang Shin* — KAIST / Cranfield University

- **11:20–12:20** — Lunch Break  

- **12:20–13:05**  
  **Safe GNC Design to Handle Polytopic Obstacles, Pointing Constraints, and Other Spacecraft**  
  *Daniel Silvestre* — NOVA University Lisbon

- **13:05–13:50**  
  **Safe Reinforcement Learning with Guarantees: Recent Advances for Continuous-Time and Discrete-Time Nonlinear Systems**  
  *Mayank Shekhar* — Université de Lorraine / CRAN

- **13:50–14:10** — Coffee Break  

- **14:10–14:55**  
  **Anti-Windup and Control Barrier Functions**  
  *Laurent Burlion* — Rutgers University

- **14:55–15:40**  
  **Enforcing Safety under Uncertainty: Control Barrier Functions for Adaptive and Sensor-Based Flight Control Systems**  
  *Johannes Autenrieb* — German Aerospace Center (DLR)

- **15:40–16:00** — Coffee Break  

- **16:00–16:45**  
  **From Simulation to Flight: An Ecosystem to Program, Test, and Tune Advanced Control Systems for UAVs**  
  *Andrea L’Afflitto* — Virginia Tech

- **16:45–17:30**  
  **Panel Discussion: Future Directions for Control Barrier Functions in Aerospace GNC**  
  *Moderator:* To be determined  
  *Panelists:* To be determined (academia & industry)

---

## Talk Abstracts

### Control Barrier Functions: Theory Overview and How to Design Them Using Dynamic Safety Margins  
**Victor Freire, Marco Nicotra — University of Colorado Boulder**

This talk provides a concise overview of the theoretical foundations of Control Barrier Functions, including the assumptions required to guarantee safety and constraint satisfaction. It then demonstrates how CBFs can be used to design safe controllers in practice. Recognizing that constructing suitable barrier functions is often challenging, the talk introduces a design approach inspired by reference governor theory, combining dynamic safety margins with CBF-based enforcement. Simple illustrative examples, such as an inverted pendulum on a cart, are used throughout.

---

### Scalable Safe Control Design: Recent Advances and Open Challenges  
**Kunal Garg — Arizona State University**

Ensuring provable safety guarantees while maintaining scalability for large-scale multi-agent systems remains a major challenge. This tutorial-style talk surveys recent advances in safe control and learning-based approaches, including methods based on learning CBFs and their extensions to multi-agent settings such as graph CBFs. Theoretical guarantees, training frameworks, experimental results, and open challenges—particularly when machine learning components are involved—are discussed.

---

### Designing Control Barrier Functions with Convex Optimisation  
**Han Wang, Kostas Margellos, Antonis Papachristodoulou — ETH Zurich & University of Oxford**

This talk addresses the long-standing challenge of designing Control Barrier Functions using convex optimization techniques. By parameterizing CBFs and feedback controllers in a structured way, infinite and non-convex invariance conditions can be relaxed into tractable optimization problems. Extensions to nonlinear systems, uncertainty, noise, input constraints, and high-relative-degree dynamics are presented.

---

### Safety-Critical Multi-UAV Cooperative Guidance via Distributed MPC and CBFs  
**Hyo-Sang Shin — KAIST / Cranfield University**

This presentation introduces a distributed MPC framework enhanced with Control Barrier Functions for safety-critical cooperative guidance of multi-UAV systems. Using ADMM-based decomposition, the approach enables scalable onboard implementation with limited information exchange. CBF constraints ensure collision avoidance and forward invariance while preserving near-optimal performance.

---

### Safe GNC Design to Handle Polytopic Obstacles, Pointing Constraints, and Other Spacecraft  
**Daniel Silvestre — NOVA University Lisbon**

This talk presents systematic CBF-based design strategies for handling complex constraint types, including polytopic obstacles, pointing constraints, and interactions with other spacecraft. A key contribution is the conversion of Constrained Convex Generators into valid CBFs, enabling the controller to encode reachable-set information and constraint feasibility guarantees.

---

### Safe Reinforcement Learning with Guarantees  
**Mayank Shekhar — Université de Lorraine / CRAN**

Recent advances in Safe Reinforcement Learning for both discrete-time and continuous-time systems are presented. The talk discusses how CBFs can be integrated into reward structures, how safety can be preserved during exploration, and how concepts such as Input-to-State Safety enable risk-aware learning with formal guarantees under input saturation and uncertainty.

---

### Anti-Windup and Control Barrier Functions  
**Laurent Burlion — Rutgers University**

This talk explores the integration of classical anti-windup schemes with Control Barrier Functions to handle output constraints. The relationship between output-to-input transformations and CBF formulations is highlighted, followed by aerospace simulation results demonstrating the effectiveness of the approach.

---

### Enforcing Safety under Uncertainty: CBFs for Adaptive and Sensor-Based Flight Control  
**Johannes Autenrieb — German Aerospace Center (DLR)**

This presentation focuses on enforcing safety constraints in aerospace systems operating under significant model uncertainty. Extensions of CBF frameworks are discussed, including integration with adaptive control architectures and sensor-based formulations. Case studies illustrate applications to overactuated and highly nonlinear flight systems.

---

### From Simulation to Flight: An Ecosystem for Advanced UAV Control  
**Andrea L’Afflitto — Virginia Tech**

An open-source ecosystem for programming, testing, and tuning advanced UAV control systems is presented. Based on a high-fidelity PyChrono simulator and a dedicated flight stack, the framework supports constrained and adaptive control designs and enables a direct path from simulation to flight testing.

---

### Panel Discussion: Future Directions for CBFs in Aerospace GNC

The workshop concludes with a moderated panel discussion synthesizing the day’s contributions. The panel will address open challenges in theory, implementation, and certification, and discuss future research and adoption pathways for Control Barrier Functions in aerospace guidance, navigation, and control.
