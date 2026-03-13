# Creative Writing Skill

A creative writing assistant skill for [Claude Code](https://claude.com/claude-code) and other AI agents following the [Agent Skills specification](https://agentskills.io).

Based on **René Nekuda's course "Základy tvůrčího psaní"** (Creative Writing Fundamentals) — 12 lessons covering the foundations of the writing craft, distilled into actionable principles and an interactive workflow.

## Install

```bash
npx skills add pavelkudrna83/creative-writing-skill
```

Or manually copy `skills/creative-writing/SKILL.md` to your `~/.claude/skills/creative-writing/` directory.

## What it does

This skill transforms Claude from a one-shot text generator into an **interactive writing partner**. Instead of immediately producing text, it guides you through the creative process:

1. **Discovers your intent** — asks about what you want to write, for whom, and what feeling it should leave
2. **Builds a story skeleton** — hero, antagonist, conflict, setting, tone
3. **Writes a first draft** — applying craft principles (no clichés, specific details, varied pacing)
4. **Iterates with you** — refines based on your feedback
5. **Reviews existing text** — structured feedback using a checklist of 9 writing principles

## Principles covered

| # | Principle | Key idea |
|---|-----------|----------|
| 1 | Beginnings | Every detail must relate to the story — no superfluous information |
| 2 | Clarity | The reader doesn't have the context in your head |
| 3 | Clichés | Replace in narrator's voice, keep in dialogue for authenticity |
| 4 | Details | Specific > generic; one good detail beats three vague ones |
| 5 | Characters | Define hero + antagonist (antagonist doesn't have to be a person) |
| 6 | Conflicts | The engine of every story — must relate to the hero/antagonist pair |
| 7 | Consistency | Track physical traits, names, world rules across the text |
| 8 | Writer type | Pantser vs. plotter — neither is better, both need revision |
| 9 | Dialogue vs. description | Alternate pacing — dialogue for speed, description for atmosphere |
| 10 | The art of selection | You can't describe everything — pick the best representative details |

## Work modes

| You come with... | Skill starts from... |
|---|---|
| "Write me a story about X" | Step 1 — discover intent |
| An outline or idea | Step 2 — build skeleton |
| Source material (article, notes) | Step 1 — find out what you want, then Step 3 |
| A finished text for review | Step 5 — structured revision |
| "Help me with this scene" | Step 3 — write, but ask about context |

## Source

Extracted from 12 video lessons of [Základy tvůrčího psaní](https://www.youtube.com/watch?v=h38UAOyA5iw&list=PLxjT-bhEcnpN76hnSJZWKR0nvrZkO-3K0) by René Nekuda. Audio was downloaded, transcribed via OpenAI Whisper API, and synthesized into this skill.

## License

MIT
