# AGENTS

Project-specific guidance:

- This repository is a scaffold for a filesystem-native workflow agent.
- Keep the scaffold simple, legible, and easy for both an LLM and a human to edit.
- Prefer plain-English markdown over rigid structure unless the user asks for stronger enforcement.
- Treat `AGENTS.md`, `SOUL.md`, `Stages/workflow.md`, and `Stages/STATUS.json` as the main project-level coordination files.
- Stage-specific intent should live inside each stage, not in a global `INTENT.md`.
- Put generic runtime behavior in `.pi/SYSTEM.md`; keep this file focused on project-specific guidance.
- Let `SOUL.md` handle voice and stance; keep this file focused on project structure and intent.
