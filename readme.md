# 🚦 SUMO-MAPPO — Multi-Agent Reinforcement Learning for Unsignalized Intersections

> **Central idea:** learn a **joint-action PPO (MAPPO-style)** policy that lets multiple vehicles cross a four-way **unsignalized** intersection safely and efficiently—outperforming a rule-based four-way-stop baseline.

---

## ✨ Key Features
* **Reproducible SUMO ⇄ Gym bridge** – custom environment with TraCI, ready for SB3.
* **Centralised training** with a single policy outputting joint actions for all approaches.
* **Rule-based baseline** (first-come-first-served) for quick benchmarking.
* **Modular reward**: collisions, delay, throughput – easy to re-weight or extend to explicit multi-objective RL.
