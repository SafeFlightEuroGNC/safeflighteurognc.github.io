---
title: Program
nav: true
---

# Workshop Program
## Pre-Conference Tutorial Workshop  
**Control Barrier Functions in Aerospace: From Foundations to Real-World Applications**

**Date:** May 4, 2026  
**Time:** 09:00–18:00 CEST  
**Location:** Universidad Carlos III de Madrid  
**Format:** Hybrid (in-person & virtual)

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


    <tr class="registration">
      <td>19:00 – 21:00</td>
      <td>EuroGNC Welcome Reception</td>
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
  *Johannes Autenrieb, Peter A. Fisher, Anuradha Annaswamy*  — German Aerospace Center (DLR) & Massachusetts Institute of Technology (MIT)

- **16:45–17:30**  
  **From Simulation to Flight: An Ecosystem to Program, Test, and Tune Advanced Control Systems for UAVs**  
  *Mattia Gramuglia, Andrea L’Afflitto* — Virginia Tech

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

**Recommended References**

[1] V. Freire and M. M. Nicotra, "[Using Dynamic Safety Margins as Control Barrier Functions](https://doi.org/10.48550/arXiv.2404.01445)," arXiv:2404.01445, 2024.

[2] V. Freire and M. M. Nicotra, "[Designing Control Barrier Functions Using a Dynamic Backup Policy](https://doi.org/10.48550/arXiv.2510.09810)," arXiv:2510.09810, 2025.

---

### Scalable Safe Control Design: Recent Advances and Open Challenges  
**Kunal Garg — Arizona State University**

Ensuring provable safety guarantees while maintaining scalability for large-scale multi-agent systems remains a major challenge. This tutorial-style talk surveys recent advances in safe control and learning-based approaches, including methods based on learning CBFs and their extensions to multi-agent settings such as graph CBFs. Theoretical guarantees, training frameworks, experimental results, and open challenges—particularly when machine learning components are involved—are discussed.

**Recommended References**

[1] S. Zhang, O. So, K. Garg, and C. Fan, "[GCBF+: A Neural Graph Control Barrier Function Framework for Distributed Safe Multiagent Control](https://doi.org/10.1109/TRO.2025.3530348)," *IEEE Transactions on Robotics*, vol. 41, pp. 1533–1552, 2025.

[2] K. Garg, S. Zhang, O. So, C. Dawson, and C. Fan, "[Learning Safe Control for Multi-Robot Systems: Methods, Verification, and Open Challenges](https://doi.org/10.1016/j.arcontrol.2024.100948)," *Annual Reviews in Control*, vol. 57, 2024.

[3] K. Garg, S. Zhang, J. Arkin, and C. Fan, "[Foundation Models to the Rescue: Deadlock Resolution in Connected Multi-Robot Systems](https://arxiv.org/abs/2404.06413)," arXiv:2404.06413, 2024.

[4] K. Garg, S. Hamilton, and C. Fan, "[Deadlock Resolution of Connected Multi-Agent Systems using Hierarchical Control](https://doi.org/10.1109/CDC56724.2024.10886421)," *IEEE Conference on Decision and Control (CDC)*, 2024.

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

**Recommended References**

[1] H. Matias and D. Silvestre, "[Hybrid Lyapunov and Barrier Function-Based Control with Stabilization Guarantees](https://arxiv.org/abs/2504.09760)," arXiv:2504.09760, 2025.

[2] H. Matias and D. Silvestre, "[Safe Navigation under Uncertain Obstacle Dynamics using Control Barrier Functions and Constrained Convex Generators](https://arxiv.org/abs/2601.07715)," arXiv:2601.07715, 2026.

---

### Safe Reinforcement Learning with Guarantees  
**Mayank Shekhar Jha — Université de Lorraine / CRAN**

Recent advances in Safe Reinforcement Learning for both discrete-time and continuous-time systems are presented. The talk discusses how CBFs can be integrated into reward structures, how safety can be preserved during exploration, and how concepts such as Input-to-State Safety enable risk-aware learning with formal guarantees under input saturation and uncertainty.

**Recommended References**

[1] S. Kanso, M. S. Jha, and D. Theilliol, "Safe Reinforcement Learning Tracking Control Based on Tunable Input-To-State Safe Control Barrier Function," *American Control Conference (ACC)*, Denver, CO, USA, 2025.

---

### Anti-Windup and Control Barrier Functions  
**Laurent Burlion — Rutgers University**

This talk explores the integration of classical anti-windup schemes with Control Barrier Functions to handle output constraints. The relationship between output-to-input transformations and CBF formulations is highlighted, followed by aerospace simulation results demonstrating the effectiveness of the approach.

**Recommended References**

[1] L. Burlion and H. de Plinval, "[Keeping a Ground Point in the Camera Field of View of a Landing UAV](https://doi.org/10.1109/ICRA.2013.6631426)," *IEEE International Conference on Robotics and Automation (ICRA)*, Karlsruhe, Germany, 2013.

[2] L. Burlion, C. Poussot-Vassal, P. Vuillemin, M. Leitner, and T. Kier, "Longitudinal Manoeuvre Load Control of a Flexible Large-Scale Aircraft," *IFAC World Congress*, Cape Town, South Africa, 2014.

[3] E. Chambon, L. Burlion, and P. Apkarian, "Output to Input Saturation Transformation: Demonstration and Application to Disturbed Linear Systems," *IEEE Conference on Decision and Control (CDC)*, Osaka, Japan, 2015.

[4] E. Chambon, L. Burlion, and P. Apkarian, "[Time-Response Shaping using Output to Input Saturation Transformation](https://doi.org/10.1080/00207179.2017.1346583)," *International Journal of Control*, vol. 91, no. 3, pp. 534–553, 2018.

---

### Enforcing Safety under Uncertainty: CBFs for Adaptive and Sensor-Based Flight Control  
**Johannes Autenrieb, Peter A. Fisher, Anuradha Annaswamy  — German Aerospace Center (DLR) & Massachusetts Institute of Technology (MIT)**

This presentation focuses on enforcing safety constraints in aerospace systems operating under significant model uncertainty. Extensions of CBF frameworks are discussed, including integration with adaptive control architectures and sensor-based formulations. Case studies illustrate applications to overactuated and highly nonlinear flight systems.

**Recommended References**

[1] J. Autenrieb and A. Annaswamy, "[Safe and Stable Adaptive Control for a Class of Dynamic Systems](https://doi.org/10.1109/CDC49753.2023.10383779)," *IEEE Conference on Decision and Control (CDC)*, Singapore, pp. 5059–5066, 2023.

[2] P. A. Fisher, J. Autenrieb, and A. M. Annaswamy, "[An Error-Based Safety Buffer for Safe Adaptive Control (Extended Version)](https://arxiv.org/abs/2510.23491)," arXiv:2510.23491, 2026.

[3] J. Autenrieb and H.-S. Shin, "[Sensor-Based Safety-Critical Control Using an Incremental Control Barrier Function Formulation via Reduced-Order Approximate Models](https://doi.org/10.23919/ACC63710.2025.11107913)," *American Control Conference (ACC)*, Denver, CO, USA, pp. 374–381, 2025.

---

### From Simulation to Flight: An Ecosystem for Advanced UAV Control  
**Mattia Gramuglia, Andrea L’Afflitto — Virginia Tech**

An open-source ecosystem for programming, testing, and tuning advanced UAV control systems is presented. Based on a high-fidelity PyChrono simulator and a dedicated flight stack, the framework supports constrained and adaptive control designs and enables a direct path from simulation to flight testing.

**Recommended References**

[1] M. Gramuglia, G. M. Kumar, and A. L'Afflitto, "[Two-Layer Adaptive Funnel MRAC with Applications to the Control of Multi-Rotor UAVs](https://doi.org/10.1109/RoMoCo60539.2024.10604361)," *International Workshop on Robot Motion and Control (RoMoCo)*, Poznan, Poland, pp. 31–36, 2024.

[2] M. Gramuglia and A. L'Afflitto, "[A Robust Multi-Constraint Funnel MRAC System With Applications to Autonomous Multi-Rotor UAVs Transporting Payloads Connected by Ropes](https://doi.org/10.2514/6.2026-2204)," *AIAA SciTech Forum*, 2026.

**Software / Code**

• [FlightStack (UAV control software stack)](https://github.com/andrealaffly/ACSL-flightstack)

• [UAV Simulator (PyChrono-based simulation framework)](https://github.com/andrealaffly/UAV_Sim_PyChrono)

---

### Panel Discussion: Future Directions for Control Barrier Functions in Aerospace GNC

The workshop concludes with a moderated panel discussion synthesizing the day’s contributions. The panel will address open challenges in theory, implementation, and certification, and discuss future research and adoption pathways for Control Barrier Functions in aerospace guidance, navigation, and control.
