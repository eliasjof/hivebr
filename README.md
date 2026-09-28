# 🐝 HiveBr
**Brazilian Open Lab for Multi-Robots**

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)
[![ROS 2](https://img.shields.io/badge/ROS%202-Humble-green.svg)](https://docs.ros.org/en/humble/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

**HiveBr** is an open-access research infrastructure designed to bridge the gap between simulation and physical hardware in the study of swarm intelligence, trajectory optimization, and multi-agent systems. 

Focused on small-scale differential drive mobile robots, the testbed allows researchers and students to validate distributed algorithms and cooperative control strategies in a hybrid environment: submit pure Python code, simulate locally, and deploy on a physical ROS 2-backed arena.

---

## 🚀 Key Features
* **Hybrid Architecture:** Develop and simulate locally in Python; execute seamlessly on a physical arena running a distributed ROS 2 and ESP32 hardware architecture.
* **Dual-Paradigm API:** Supports both purely distributed behaviors (Agent-centric) and global optimization algorithms (Centralized-centric).
* **Open Access Submission:** Submit experiments via our online workflow and receive detailed telemetry logs, odometry data, and video recordings of the physical execution.

---

## 🛠️ Installation

Clone the repository and install the Python simulation package in editable mode:

```bash
git clone [https://github.com/eliasjof/hivebr.git](https://github.com/your-org/hivebr.git)
cd hivebr
pip install -e .
