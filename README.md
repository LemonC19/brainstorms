# Brainstorms

A Hermes Agent skill for structured brainstorming before creative work. It helps clarify intent, explore tradeoffs, and agree on a design before implementation begins.

## Contents

- `SKILL.md` — the complete skill definition, including its metadata and instructions.

## Install

Place the skill at:

```text
~/.hermes/skills/brainstorms/SKILL.md
```

Start a new Hermes session, or run `/reset` in the current session. Hermes discovers the skill automatically; no registration is required.

Verify the installation with:

```bash
hermes skills list | grep brainstorms
```

## Use

Invoke the skill with `/brainstorms`, optionally followed by a task. You can also ask Hermes to use it for creative work such as planning features, designing components, changing behavior, or preparing other new projects.
