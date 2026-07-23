# AI Assistant Instructions

This file guides AI coding assistants (Claude Code, Cursor, etc.) when working in this repository.

## Project Context

- **Assignment:** A1W1 – Environment and AI Toolchain (Week 1 capstone)
- **Purpose:** Establish a professional JavaScript development environment and AI-assisted workflow
- **Language:** JavaScript (ES2023)
- **Package manager:** npm

## Coding Conventions

- Use clear, readable JavaScript with modern ES2023 syntax
- Prefer small, focused changes over large refactors
- Match existing file structure and naming in the repo
- Keep documentation accurate and in sync with the codebase

## Git & Commits

Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

| Type | Use for |
|------|---------|
| `feat` | New features or project setup |
| `docs` | Documentation changes |
| `fix` | Bug fixes or corrections |
| `chore` | Maintenance tasks (dependencies, tooling) |

Examples:

```text
feat: initialize capstone repository
docs: create project README
docs: add CLAUDE instructions
```

## AI Workflow Guidelines

- Review all AI-generated code and documentation before committing
- Ask for explanations when learning new concepts
- Use AI to improve docs, suggest best practices, and assist with debugging
- Do not commit secrets (`.env`, API keys, credentials)

## Repository Files

| File | Role |
|------|------|
| `README.md` | Project overview and setup instructions |
| `CLAUDE.md` | This file — AI assistant guidelines |
| `package.json` | Node.js project metadata |
| `.gitignore` | Git ignore rules |
| `LICENSE` | MIT License |
