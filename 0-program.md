---
title: Program
nav: true
---

# Workshop Program
## Pre-Conference Tutorial Workshop  
**Control Barrier Functions in Aerospace: From Foundations to Real-World Applications**

**Date:** May 4, 2026  
**Core Workshop Time:** 09:00–18:00 CEST  
**Location:** Universidad Carlos III de Madrid, Madrid, Spain  
**Format:** Hybrid (in-person & virtual)

*The schedule below is aligned with the official EuroGNC time slots for coffee breaks and lunch. The concluding panel discussion may extend slightly beyond 18:00.*

<table class="workshop-schedule">
  <thead>
    <tr class="schedule-title">
      <th colspan="2">
        Workshop Schedule
      </th>
    </tr>
    <tr>
      <th style="width: 20%;">Time</th>
      <th>Session</th>
    </tr>
  </thead>

  <tbody>
    <tr class="coffee">
      <td>08:30 – 09:00</td>
      <td>Morning Coffee & Arrival</td>
    </tr>

    <tr>
      <td>09:00 – 10:30</td>
      <td>Invited Tutorial Lectures (Session I)</td>
    </tr>

    <tr class="coffee">
      <td>10:30 – 11:00</td>
      <td>Coffee Break</td>
    </tr>

    <tr>
      <td>11:00 – 13:00</td>
      <td>Invited Tutorial Lectures (Session II)</td>
    </tr>

    <tr class="lunch">
      <td>13:00 – 14:00</td>
      <td>Lunch Break</td>
    </tr>

    <tr>
      <td>14:00 – 15:30</td>
      <td>Invited Tutorial Lectures (Session III)</td>
    </tr>

    <tr class="coffee">
      <td>15:30 – 16:00</td>
      <td>Afternoon Coffee</td>
    </tr>

    <tr>
      <td>16:00 – 18:15</td>
      <td>Invited Tutorial Lectures & Panel Discussion</td>
    </tr>


    <tr class="social">
      <td>19:00 – 21:00</td>
      <td>Welcome Cocktail</td>
    </tr>
  </tbody>
</table>


---

## Tentative Schedule

- **09:00–09:10** — Welcome & Opening Remarks  

- **09:10–09:55**  
  **Control Barrier Functions: Theory Overview and How to Design Them Using Dynamic Safety Margins**  
  *Victor Freire, Marco Nicotra* — University of Colorado Boulder

- **09:55–10:40**  
  **Scalable Safe Control Design: Recent Advances and Open Challenges**  
  *Kunal Garg* — Arizona State University

- **10:40–11:25**  
  **Designing Control Barrier Functions with Convex Optimisation**  
  *Han Wang, Kostas Margellos, Antonis Papachristodoulou* — ETH Zurich & University of Oxford

- **11:25–12:10**  
  **Safety-Critical Multi-UAV Cooperative Guidance via Distributed MPC and Control Barrier Functions**  
  *Hyo-Sang Shin* — KAIST / Cranfield University

- **12:10–13:00**  
  **Safe GNC Design to Handle Polytopic Obstacles, Pointing Constraints, and Other Spacecraft**  
  *Daniel Silvestre* — NOVA University Lisbon

- **13:00–14:00** — **Lunch Break**  

- **14:00–14:45**  
  **Safe Reinforcement Learning with Guarantees: Recent Advances for Continuous-Time and Discrete-Time Nonlinear Systems**  
  *Mayank Shekhar* — Université de Lorraine / CRAN

- **14:45–15:30**  
  **Anti-Windup and Control Barrier Functions**  
  *Laurent Burlion* — Rutgers University

- **15:30–16:00** — **Afternoon Coffee Break**  

- **16:00–16:45**  
  **Enforcing Safety under Uncertainty: Control Barrier Functions for Adaptive and Sensor-Based Flight Control Systems**  
  *Johannes Autenrieb* — German Aerospace Center (DLR)

- **16:45–17:30**  
  **From Simulation to Flight: An Ecosystem to Program, Test, and Tune Advanced Control Systems for UAVs**  
  *Andrea L’Afflitto* — Virginia Tech

- **17:30–18:15**  
  **Panel Discussion: Future Directions for Control Barrier Functions in Aerospace GNC**  
  *Moderator:* To be determined  
  *Panelists:* Academia & industry

*Registration for the conference runs in parallel from 17:30 onward.*

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

### Panel Discussion: Future Directions for Control Barrier Functions in Aerospace GNC

The workshop concludes with a moderated panel discussion synthesizing the day’s contributions. The panel will address open challenges in theory, implementation, and certification, and discuss future research and adoption pathways for Control Barrier Functions in aerospace guidance, navigation, and control.
