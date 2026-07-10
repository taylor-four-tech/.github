---
name: Pull Request
about: Standard PR template for all Taylor Four Tech repos
---

## What
<!-- Brief description of what this PR does -->

## Why
<!-- Why is this change needed? Link to issue if applicable -->

## How
<!-- How was this implemented? Key design decisions -->

## Testing
- [ ] Tests pass locally (`make test` or `pytest`)
- [ ] Linter passes (`make lint` or `ruff check .`)
- [ ] Docker build succeeds (if applicable)
- [ ] Health endpoint verified (if applicable)

## Checklist
- [ ] Conventional commit messages used
- [ ] No secrets or API keys in code
- [ ] AGENTS.md updated (if architecture changed)
- [ ] Documentation updated (if user-facing changes)
