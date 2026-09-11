# ROOT_ict Advanced Logic Gate Simulator & Assessment Engine

An interactive, responsive, and segment-timed digital logic circuit simulator built for secondary and advanced ICT students. Designed to evaluate foundational and complex digital logic design through real-time truth table verification, hands-on wiring, and automated evaluation reports.

---

## Key Features

* **Interactive Wiring Canvas:** Drag-and-drop or tap-to-place logic gates (`AND`, `OR`, `NOT`, `NAND`, `NOR`, `XOR`) with real-time dynamic SVG wire drawing.
* **Fully Responsive & Touch Compatible:** Optimized for desktop drag-and-drop as well as touch devices (tablets and smartphones) with tap-to-add shortcuts and mobile-optimized drag handlers.
* **12 Timed Examination Scenarios:**
  * **Basic Scenarios:** Smart street lighting, secure ATM access, and building fire alarms.
  * **Intermediate Scenarios:** Industrial cooling fans, water level tanks, bank vault logic, and conveyor controls.
  * **Advanced Multi-Input & Multi-Output Scenarios:** Dual-language (English & Sinhala) complex problems including 4-bit binary vault validation, gym access controllers, and goldfish aquarium monitoring.
* **Automated Truth Table Evaluation:** Evaluates custom circuit wire paths through recursive dependency sorting across all possible binary permutations before granting submission approval.
* **Intermission & Exam Time Management:** Segmented timers per challenge, auto-save failover, and automated rest breaks (10-minute and 30-minute intervals).
* **Automated Assessment Report:** Compiles student attempts, wire geometries, remaining timestamps, and pass/fail states into a downloadable structured JSON answer sheet.

---

## Supported Components

| Gate | Symbol Logic | Inputs |
| :--- | :--- | :--- |
| **AND** | $Y = A \cdot B$ | 2 |
| **OR** | $Y = A + B$ | 2 |
| **NOT** | $Y = \bar{A}$ | 1 |
| **NAND** | $Y = \overline{A \cdot B}$ | 2 |
| **NOR** | $Y = \overline{A + B}$ | 2 |
| **XOR** | $Y = A \oplus B$ | 2 |

---

## Getting Started

### Local Setup
No build tools, bundlers, or external dependencies are required.

1. Clone or download the repository:
   ```bash
   git clone [https://github.com/your-username/root-ict-logic-simulator.git](https://github.com/your-username/root-ict-logic-simulator.git)
