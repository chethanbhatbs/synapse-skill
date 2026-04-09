# Learnings — Claude Code Skill

Capture and document what you learned from any task — new tools, technologies, skills, concepts, or insights.

## Prerequisites

- [Claude Code](https://claude.ai/claude-code) CLI installed
- GitHub CLI (`gh`) for one-line install

## Installation

**One-line install:**

```bash
gh repo clone chethanbhatbs/learnings-skill ~/.claude/skills/learnings
```

**Manual install:**

```bash
git clone https://github.com/chethanbhatbs/learnings-skill.git
cp -r learnings-skill/ ~/.claude/skills/learnings/
```

**Verify it's installed:**

```bash
ls ~/.claude/skills/learnings/
```

You should see `SKILL.md` (and any other skill files).

## Usage

```
/learnings              # Capture learnings from current task
/learnings [topic]      # Capture learnings about a specific topic
```

### What it does

Invoke after finishing a task or when you want to record insights. Captures:

- What was learned
- Tools/technologies involved
- Key takeaways
- Practical tips for next time

Learnings are saved to your project memory so future conversations can reference them.



## How Claude Code Skills Work

Skills are markdown files in `~/.claude/skills/` that give Claude Code specialized instructions for specific tasks. When you invoke a skill (e.g., `/Learnings`), Claude reads the `SKILL.md` and follows its instructions.

## Uninstall

```bash
rm -rf ~/.claude/skills/learnings
```

## License

MIT
