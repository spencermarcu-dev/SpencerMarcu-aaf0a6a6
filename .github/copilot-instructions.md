@spencermarcu

# Copilot coding agent instructions

These instructions are for AI coding agents working in this repository.

## Repository overview

- This is a lightweight profile repository with minimal tooling.
- Keep changes small, focused, and easy to review.

## How to work in this repo

- Prefer precise, surgical edits over refactors.
- Do not introduce new build/test/lint tooling unless explicitly requested.
- Do not add dependencies (no `npm install`, `pip install`, etc.) unless required by the task.

## Validation

- If there are existing checks/tests, run them.
- If there are no existing checks/tests (common here), do not invent new ones; instead, manually verify changes (e.g., file contents/format).

## Files and conventions

- Keep `README.md` content simple and readable on GitHub.
- Avoid adding generated artifacts, lockfiles, or large binaries.
- Use Markdown for docs; keep formatting consistent with existing style.
