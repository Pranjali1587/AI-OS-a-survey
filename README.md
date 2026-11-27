AI-OS: A Survey

Are AI agents safe when they run commands on an operating system? A comparative survey of research on the safety of AI agents that execute shell commands, edit files and call tools on real machines.



Overview

Language model agents have moved from writing text to acting on computers. A chatbot's mistake stays on the screen. An agent's mistake can change files, leak credentials or stop processes, and some of that cannot be undone.

The research on this topic is split across sub fields (how agents learn to use tools, how their reasoning is attacked, how their safety is tested, how their actions are constrained). Each uses different environments, threat models and metrics, so the results are hard to compare. This project brings them together.

Core question: Are current AI-OS agents safe when judged by their own operational and benchmark criteria?

Short answer from the survey: Not reliably. Safety fails at every level of test realism, from visible reasoning to a live Ubuntu system, and each defence we reviewed leaves a measurable gap
