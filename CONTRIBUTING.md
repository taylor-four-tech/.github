# Contributing to Taylor Four Tech Projects

## Development Standards

All repositories follow the [Taylor Four Tech Development Standards](https://github.com/taylor-four-tech/ai-ops-wiki/blob/main/engineering/development-standards.md).

## Quick Reference

### Branch Workflow
1. Branch from `main`: `git checkout -b feat/<description>`
2. Make changes
3. Run tests: `make test` (or `python -m pytest tests/ -q --tb=short`)
4. Run linter: `make lint` (or `ruff check .`)
5. Commit with conventional messages: `feat: add feature X`
6. Push and open PR
7. Wait for CI and review

### Commit Messages
Conventional commits required:
- `feat:` — New feature
- `fix:` — Bug fix
- `docs:` — Documentation
- `test:` — Tests
- `refactor:` — Restructuring
- `chore:` — Tooling/deps
- `ci:` — CI/CD changes

### For AI Agents
Agents follow the same workflow. Check the repo's `AGENTS.md` for project-specific context before making changes.

### CI/CD
All deployable services use GitHub Actions for CI/CD. See the [CI/CD Pipeline Reference](https://github.com/taylor-four-tech/ai-ops-wiki/blob/main/engineering/cicd-pipeline.md).

### Standards Enforcement
[Wingman Code](https://github.com/taylor-four-tech/wingman-code) enforces these standards on all builds it produces. Any repo can be scanned for compliance.
