# Skills Catalog

Each folder in this directory is an installable skill. Keep skill folders directly under `skills/` so users can copy one folder at a time into their agent's skills directory.

| Skill | Best for | Install folder |
| --- | --- | --- |
| Slow Down | Agent-agnostic pacing, relational awareness, and knowing when to pause before action. | `skills/slow-down` |
| Slow Down Flow | Helping a person move from mental noise or avoidance into one tiny embodied action. | `skills/slow-down-flow` |

## Layout

```text
skills/
  README.md
  slow-down/
    SKILL.md
    agents/openai.yaml
  slow-down-flow/
    SKILL.md
    agents/openai.yaml
```

## Naming

- `slow-down` is the main agent-pacing skill.
- `slow-down-flow` is the practical self-regulation/action flow.

When adding a new skill, create a new folder under `skills/`, include a `SKILL.md` file with frontmatter, and add optional agent UI metadata under `agents/`.
