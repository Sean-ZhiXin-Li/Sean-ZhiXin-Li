<h1 align="center">Hi, I'm Sean (Zhixin Li)</h1>

<p align="center">
High school student · Self-directed researcher · AI × Spacecraft Control
</p>

---

## 🛰️ About Me

I am interested in spacecraft autonomy: how software, control, and learning systems can help a spacecraft make better propulsion decisions in uncertain environments.

My work focuses on building reproducible simulations, explicit controllers, and engineering logs. I treat failure as data, not as something to hide.

> Trajectories drift. Controllers adapt. Failure is telemetry.

---

## 🚀 Flagship Project — Spacecraft AI Controller

A long-term research-engineering project exploring **autonomous orbital insertion and propulsion control in a physics-based 2D orbital environment**.

### Current Research Stage

**Phase36C — Non-Crossing Geometry Diagnosis**

The project evolved from simple rule-based controllers and PPO experiments into a structured investigation of orbital transfer geometry and recoverability.

Recent milestones:

* **Phase34:** Developed a robust post-cross synchronization controller and recoverability framework.
* **Phase36B:** Benchmarked four transfer-family designs across a reduced orbital test suite.
* **Phase36C:** Diagnosed the remaining non-crossing cases and identified the primary bottleneck as **upstream crossing-generation**, not post-cross stabilization.

### Key Findings

* Multiple transfer families converge to the same crossing basin.
* Recoverability after crossing is largely solved in the current simulator.
* The remaining challenge is generating new Phase34-compatible crossings from difficult initial conditions.
* Geometric metrics can improve without necessarily creating new crossings.

### What I Built

* Physics-based orbital simulation environment
* Explicit phase-structured spacecraft controllers
* PPO and imitation-learning baselines
* Transfer-family benchmark framework
* Recoverability and crossing-basin analysis tools
* Failure-mode diagnostics and benchmark evaluation pipelines
* Detailed engineering and research logs documenting both successes and failures

### Current Research Question

> Which parameterized transfer trajectory can generate new recoverable crossings among the remaining non-crossing orbital cases?

### Long-Term Direction

The long-term goal is to investigate how planning, control, and learning-based methods can cooperate in autonomous spacecraft guidance, eventually extending beyond reactive control toward trajectory-generation and decision-making systems.

🔗 Repo: https://github.com/Sean-ZhiXin-Li/spacecraft-ai-controller

---

## 🧪 the-new

A unified engineering workspace for building lab-ready systems habits through real execution.

Current focus:

- Python engineering from scratch
- Linux / WSL workflow
- Git discipline and repo hygiene
- Debugging and reproducibility
- Config → run → metrics → verification pipelines
- Small AI / simulation-oriented engineering experiments

This repository is not designed to look flashy. It is designed to show process: how I set up systems, run experiments, record outputs, debug failures, and gradually turn isolated scripts into reproducible engineering workflows.

It connects directly to my larger AI orbital-control project by strengthening the engineering foundation behind reliable experiments: environment setup, command-line workflow, metrics, validation, and documentation.

🔗 Repo: https://github.com/Sean-ZhiXin-Li/the-new

---

## 🛠️ Tech Foundations

I am also building foundations in areas that support spacecraft autonomy:

- Control systems
- Robotics
- Embedded systems
- Reinforcement learning
- Simulation engineering
- Basic CAD / CubeSat structure exploration

🔗 Repo: https://github.com/Sean-ZhiXin-Li/tech-foundations

---

## 💻 Languages Used

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Sean-ZhiXin-Li&layout=compact&langs_count=6&hide=html,css&theme=github_dark" />
</p>

---

## 📓 Research Philosophy

I care about process integrity.

- Logs preserve the reasoning path
- Bugs reveal structure
- Negative results are evidence
- Reproducibility matters more than appearance
- Progress is often spiral, not linear

Open-ended engineering projects taught me persistence more than drills or competitions did.

---

## 🌌 Long-Term Direction

I want to keep working toward spacecraft autonomy: controllers that can adapt, degrade gracefully, and survive uncertainty.

My current work is still early and limited to simulation, but it gives me a concrete path to learn control, AI, physics, and engineering through one long-term system.

---

## 📬 Connect

- GitHub: https://github.com/Sean-ZhiXin-Li
- Email: tlizxin209625@gmail.com

---

<p align="center">
  <b>Focus:</b> AI × Spacecraft Control · Simulation · Reproducible Engineering
</p>
