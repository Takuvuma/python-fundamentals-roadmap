# AGENTS.md

Purpose
-------
This file provides concise, actionable guidance for AI coding agents working in this repository.

Current repo state
------------------
- Repository appears minimal / empty. There are no obvious build, test, or docs files present.

How an agent should proceed
--------------------------
- Explore the workspace for added files (tests, pyproject.toml, requirements.txt). Link rather than copy any found docs.
- If no build/test commands are present, ask the repository owner for the preferred Python version, test runner, and any setup steps before making changes.
- When modifying code, follow these principles:
  - Keep changes minimal and focused.
  - Prefer adding tests for behavioral changes.
  - Do not assume third-party services or credentials are available.

Suggested quick checks
----------------------
- Look for: `pyproject.toml`, `requirements.txt`, `setup.cfg`, `tox.ini`, `Pipfile`, `tests/`, or `README.md`.
- If `pyproject.toml` or `requirements.txt` exists, install dependencies into a venv and run the project's test runner.

Adding more instructions
------------------------
- If you (maintainer) want richer agent guidance, add a `.github/copilot-instructions.md` or expand this file with sections for:
  - Build and test commands
  - Recommended Python versions and environment setup
  - Code style and linters to run
  - Where to run integration tests or how to spin local services

Contact / feedback
------------------
- Agent should prompt the repository owner for missing or ambiguous info before making substantive edits.
