# MASAI: Modular Architecture for Software engineering AI agents

📰 [arxiv preprint](https://arxiv.org/abs/2406.11638)


A common method to solve complex problems in software engineering is to divide the problem into multiple sub-problems. Inspired by this, we propose a Modular Architecture for Software-engineering AI (MASAI) agents, where different LLM-powered sub-agents are instantiated with well-defined objectives and strategies tuned to achieve those objectives.

Our modular architecture offers several advantages:

1. employing and tuning different problem-solving strategies across sub-agents,
2. enabling sub-agents to gather information from different sources scattered throughout a repository, and
3. avoiding unnecessarily long trajectories which inflate costs and add extraneous context.

MASAI achieves a competitive performance (28.33% resolution rate) on the popular and highly challenging SWE-bench Lite dataset consisting of 300 GitHub issues from 11 Python repositories at less than 2$ per issue cost on average.
