# Slow Down

Skills for agents and people who want to move with more contact, less noise, and better timing.

Built around one shared instinct:

Slow down when speed starts to bypass awareness.
Return to action when slowness starts to become avoidance.

Each skill is as short as it can be while still holding its stance. The work of noticing is returned to the agent or person who meets it.

## Current Skills

Four separately invokable skills: `/slow-down`, `/slow-down-flow`, `/slow-down-crosswind`, `/slow-down-bridges`, and `/slow-down-wonder`.

| Skill | Use it for | Folder |
| --- | --- | --- |
| Slow Down | Agent pacing. Slows only when speed risks bypassed awareness or human contact. | `skills/slow-down` |
| Slow Down Flow | Human return. One tiny embodied action before announcing or optimizing. | `skills/slow-down-flow` |
| Slow Down Crosswind | Consequential-plan premortems. Uses failure as contact, then returns to one smaller reversible move. | `skills/slow-down-crosswind` |
| Slow Down Bridges | Connection re-readings. Re-reads a gesture as contact before the verdict hardens. No labels, diagnosis, compatibility scoring, scripts, or prescribed replies. | `skills/slow-down-bridges` |
| Slow Down Wonder | A pause when certainty arrives unusually quickly. Holds the space open for what may be being skipped. Manual activation only. | `skills/slow-down-wonder` |

## Design stance

Each skill carries a centering sentence, a sense of when to use it, a floor below which it will not go, and one ending commitment. The rest is returned.

- The agent keeps contact, in its own words.
- The person takes one real step.
- The plan feels its crosswind before it hardens.
- The gesture is re-read before the verdict hardens.
- The closure is noticed before it settles.

## Which one should I install?

Install `slow-down` when you want the agent itself to carry the discipline of pace.

Install `slow-down-flow` when you want a practical human reset for noisy, avoidant, overstimulated moments.

Install `slow-down-crosswind` when you want a contained premortem for a consequential plan.

Install `slow-down-bridges` when you want a pause before interpreting someone's behavior as distance or rejection.

Install `slow-down-wonder` when you want a posture for premature certainty. Manual activation only — wonder imposed is not wonder.

Install them together for the full loop.

## Manual install

Once published in the Claude community marketplace, install the plugin from Claude Code:

```text
claude plugin install slow-down
```

For local testing from a clone of this repository:

```text
claude --plugin-dir .
```

The skill folders remain plain `SKILL.md` directories. If your agent supports manual skill installation, you can still copy individual folders from `skills/`.

## How to use the skills

Invoke the skill shortcut when you want the agent to shift posture:

```text
/slow-down Help me draft this hard message without flattening the person receiving it.
/slow-down-flow I am scattered and want to post the plan before doing it. Help me take one tiny action first.
/slow-down-crosswind Premortem this launch plan without turning it into fear.
/slow-down-bridges They keep turning everything into a debate and I'm about to withdraw. Help me see it without labeling them.
/slow-down-wonder I closed on this too fast. Hold the space open without directing it.
```

The folder names are the stable skill names.

## Scope note

Slow Down is reflective guidance, not therapy, diagnosis, crisis support, or medical advice.

## Repository layout

```text
.claude-plugin/
  plugin.json
skills/
  slow-down/
  slow-down-flow/
  slow-down-crosswind/
  slow-down-bridges/
  slow-down-wonder/
LICENSE
CHANGELOG.md
```

Each skill folder contains a `SKILL.md` file.

## License

MIT. See `LICENSE`.
