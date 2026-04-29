# ClawGym

## ✨ News

- **[30 Apr 2026]** We release the paper **ClawGym: A Scalable Framework for Building Effective Claw Agents**.

## 💡 Overview

**ClawGym** is a scalable framework for building, training, and evaluating Claw-style personal agents across realistic local workspace environments.

ClawGym supports the full lifecycle of personal-agent development. It first constructs **ClawGym-SynData**, a diverse dataset of **13.5K executable tasks** synthesized from persona-driven intents and skill-grounded operations. Each task is paired with a realistic mock workspace and hybrid verification mechanisms, enabling reproducible execution and automated evaluation.

Based on these synthesized tasks, we collect interaction trajectories through black-box rollouts and use them to train a family of capable Claw-style models, termed **ClawGym-Agents**. We further introduce **ClawGym-RL**, a lightweight reinforcement-learning pipeline that parallelizes rollouts across per-task sandboxes, supports both Docker-based and Docker-free backends, and learns directly from outcome rewards.

To support reliable evaluation, we build **ClawGym-Bench**, a **200-instance benchmark** calibrated through automated filtering and human-LLM review.


