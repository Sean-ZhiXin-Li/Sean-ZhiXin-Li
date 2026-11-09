# Hi, I'm Sean (Zhixin Li)

**Robotics & autonomous systems · Dynamics and control · Perception and state estimation · Spacecraft GNC**

I'm a high school student exploring robotics and autonomous systems through projects. I like building simulations, tracing unexpected behavior, and working out which assumption failed.

Voyager and Cassini helped spark my interest in exploration. That curiosity now connects my work on robot manipulation and spacecraft control: how can a system make useful decisions from imperfect measurements, and what should it do when a plan stops matching reality?

## What I'm working on

**Independent orbital-control research.** [Spacecraft AI Controller](https://github.com/Sean-ZhiXin-Li/spacecraft-ai-controller) began with PPO and explicit-controller comparisons and grew into a study of recoverable insertion. The latest public work explores fuel-constrained planning, velocity-bias estimation, delayed fault diagnosis and bidirectional transfers in simplified 2D dynamics. In one 24-task simulator holdout with a shared 4,400-day deadline, bidirectional search achieved capture and sampled survival on 24/24 tasks, compared with 11/24 for the matched outward-only baseline. The [experiment record](https://github.com/Sean-ZhiXin-Li/spacecraft-ai-controller/blob/ff4d06229016511d38bba2c432b990e0c38be001/project_log/2026-10-23_multiregime_transfer_planning.md) also preserves the initial 0/8 development result at the shorter deadline. These are bounded simulation results, not flight validation or RL achievements.

**Robot perception and feedback.** I work on simulated Franka plug insertion in NVIDIA Isaac Sim, exploring RGB-D perception, FoundationPose pose estimation, feedback control and contact recovery, with remote research guidance from the University of Michigan's [ROAHM Lab](https://www.roahmlab.com/). This work is mentor-guided and simulation-based; unpublished lab results stay private.

## Selected public repositories

| Repository | What you'll find |
|---|---|
| [spacecraft-ai-controller](https://github.com/Sean-ZhiXin-Li/spacecraft-ai-controller) | My main public research project: explicit control, orbital geometry, estimation and reproducible experiment records. Its README separates current evidence, negative results and a staged long-term autonomy roadmap. |
| [the-new](https://github.com/Sean-ZhiXin-Li/the-new) | A collection of programming and engineering exercises, including C++, linear algebra and an AI engineering playground. It is a working exercise collection rather than a documented end-to-end research system. |
| [tech-foundations](https://github.com/Sean-ZhiXin-Li/tech-foundations) | A foundations archive marked **Frozen (2025)**, covering control, simulation, experiment logging and hardware awareness. I retain it as earlier learning context. |

## Questions I'm learning to answer

- How can dynamics, geometry and uncertainty estimates help a planner choose actions that remain recoverable?
- When should a controller wait for better evidence, adjust a plan, recover, or stop?
- How can perception and contact information support manipulation without hiding privileged simulator assistance?

I'm continuing to build my foundations in mathematics, control and estimation, C++ and embedded systems. Longer term, I want to explore how these pieces support resilient robots and space probes. Those are learning directions, separate from what my current experiments demonstrate.

I value clear baselines, useful failure logs and claims that another person can check. I welcome thoughtful technical conversations and collaboration around those questions.

**Contact:** [tlizxin209625@gmail.com](mailto:tlizxin209625@gmail.com)
