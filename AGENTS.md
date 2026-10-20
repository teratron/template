# Agents Instructions, Guidelines & Engineering Standards

## 1. Language Policy

### 1.1 Technical Content (English ONLY)

- **Codebase**: All identifiers (variables, functions, classes), comments, and docstrings.
- **Documentation**: Technical guides, READMEs, and implementation notes.
- **Process**: Commit messages, PR descriptions, and issue titles.
- **Environment**: Error messages, logs, and API definitions.

### 1.2 Communication

- Use the project's primary language for discussions, planning, and conversational feedback.

## 2. Commit Conventions

Follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/):

```
<type>[optional scope]: <description>

[optional body]

[optional footer]
```

| Type | When to use |
| --- | --- |
| `feat` | New feature |
| `fix` | Bug fix |
| `docs` | Documentation only |
| `refactor` | Code change — no fix, no feature |
| `test` | Adding or updating tests |
| `chore` | Build, CI, dependency, or config tasks |
| `perf` | Performance improvement |

Breaking changes: append `!` after type — `feat!: drop Node 16 support`.

## 3. Branch Naming

```
<type>/<short-kebab-description>
```

Examples: `feat/user-auth`, `fix/null-pointer`, `docs/api-reference`, `chore/update-deps`.

## 4. Code Review Protocol

- Address all review comments before requesting re-review.
- Do **not** force-push during an open review cycle.
- Mark resolved threads as resolved only after the fix is pushed.
- Keep PRs small and focused — one concern per PR.

## 5. Completion Protocol (Mandatory Checklist)

Before concluding any development task, every agent MUST verify the following checklist:

- [ ] Verify code functionality and behavior.
- [ ] Ensure directly related documentation is updated.
- [ ] All code, identifiers, comments, and technical docs are in English.
- [ ] Commit message follows Conventional Commits format.
- [ ] `CHANGELOG.md` updated under `[Unreleased]` if the change is user-facing.
