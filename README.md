# Coding Standards Skill

Universal coding standards and practical engineering patterns for TypeScript, JavaScript, React, and Node.js projects.

## What It Does

`coding-standards` gives an agent a consistent baseline for writing maintainable code:

- readable naming
- simple implementation choices
- immutable updates
- type-safe interfaces
- predictable error handling
- React component and hook conventions
- API response consistency
- testing and review expectations

## Use It For

- Starting a new frontend or full-stack feature.
- Reviewing generated code for maintainability.
- Keeping TypeScript, JavaScript, React, and Node.js work consistent across projects.
- Teaching an agent your preferred default engineering style.

## Install

```bash
npx skills add Jorgut/coding-standards-skill
```

Manual install:

```bash
git clone https://github.com/Jorgut/coding-standards-skill.git
```

Then place or symlink the folder into your agent's skill directory, such as `~/.codex/skills/`, `~/.claude/skills/`, or `~/.config/opencode/skills/`.

## How To Use

Ask your agent to use the skill before implementation or review:

```text
Use coding-standards while implementing this TypeScript feature.
Review this React component with coding-standards.
Apply my coding standards before making the final commit.
```

## Example Checks

The skill should push the agent toward:

- small, direct implementations before abstractions
- typed interfaces instead of loose `any`
- immutable updates in React state
- predictable error handling
- tests for behavior that can regress

## Core Principles

- Readability first.
- Keep solutions simple.
- Avoid speculative abstractions.
- Prefer type safety over `any`.
- Use immutable updates.
- Handle errors intentionally.
- Test meaningful behavior.

## Scope

This skill is intentionally broad. It is best used as a baseline alongside framework-specific skills, project-specific `AGENTS.md` rules, or a dedicated review skill.

It does not replace framework-specific guidance for Django, Spring Boot, SwiftUI, database design, security review, or accessibility audits. Pair it with those skills when the project needs them.

## License

MIT. See [LICENSE](LICENSE).
