# Slow Down

Skills for agents and people who want to move with more contact, less noise, and better timing.

This repository is a growing collection built around one shared instinct:

Slow down when speed starts to bypass awareness.

Return to action when slowness starts to become avoidance.

Feel the crosswind before a commitment hardens.

## Philosophy

Slow is not a mood. It is a kind of discernment.

The best agents should not simply produce more output. They should notice when speed is flattening a human moment, when certainty arrives too quickly, when abstraction replaces contact, or when a task is technically easy but emotionally expensive.

The best personal reset does not shame the mind for looking for shortcuts. It helps the person notice the loop, reduce the next step, move the body, and reward the completed action instead of the imagined one.

The best premortem does not turn fear into a ritual. It lets a person briefly visit the future where a plan went wrong, notice who or what paid the cost, and return with a smaller, more honest, more reversible move.

That is the quiet shape of this collection:

```text
Stay in contact.
Make the next step smaller.
Act before performing the intention.
Return without shame.
Let imagined failure reveal contact, then come back.
```

## Current Skills

As a Claude Code plugin, Slow Down contains three separately invokable skills: `/slow-down`, `/slow-down-flow`, and `/slow-down-crosswind`.

| Skill | Use it for | Folder |
| --- | --- | --- |
| Slow Down | Agent pacing. It helps an agent preserve human connection, avoid rushing relational or identity-forming moments, and intervene only when speed risks numbness or bypassed understanding. | `skills/slow-down` |
| Slow Down Flow | Human return. It helps a person move from noisy thinking, avoidance, or premature announcement into one tiny embodied action and a grounded record of completion. | `skills/slow-down-flow` |
| Slow Down Crosswind | Consequential-plan premortems. It helps a person expose hidden assumptions and human cost before a plan hardens, then return to one smaller reversible move. | `skills/slow-down-crosswind` |

## Which one should I install?

Install `slow-down` when you want the agent itself to carry the discipline of pace.

It is for conversations where faster is not automatically better: drafting a difficult message, making a decision that affects people, building something from motive rather than momentum, or noticing that "quick" has become a way to avoid feeling the real cost.

Install `slow-down-flow` when you want a practical human reset.

It is for the moment when the mind is noisy, the tabs are multiplying, the body has not moved yet, and announcing the intention would give the reward too early.

Install `slow-down-crosswind` when you want a contained premortem for a consequential plan.

It is for the moment when "what am I missing?" is not lightweight critique but a real-cost question: a launch, commitment, relational move, identity-forming decision, or plan where being wrong would quietly charge someone.

Install the current skills together when you want the full loop:

```text
The agent keeps contact.
The person takes one real step.
The plan feels its crosswind before it hardens.
The work becomes evidence.
```

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
```

The folder names are the stable skill names.

## Scope note

Slow Down is reflective guidance, not therapy, diagnosis, crisis support, or medical advice.

## Design principles

- Prefer contact over output volume.
- Ask one precise question instead of performing care.
- Do not moralize speed, slowness, discipline, or avoidance.
- Make the next action smaller than the resistance.
- Reward completion, not announcement.
- Use failure as contact, not catastrophe.
- Keep premortems proportionate and reversible.
- Slow down only enough to return.

## Repository layout

```text
.claude-plugin/
  plugin.json
skills/
  slow-down/
  slow-down-flow/
  slow-down-crosswind/
LICENSE
CHANGELOG.md
```

Each skill folder contains a `SKILL.md` file.

## License

MIT. See `LICENSE`.

## The long game

If AI is going to sit this close to human thought, it should learn to move with conscience, timing, and restraint.

This repository is a small pressure point toward that future: agents that do not rush the tender parts, people who do not confuse saying with doing, and tools that help us become more present instead of more automatic.
