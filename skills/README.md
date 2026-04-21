# 🛠️ Skills — Drop-in Agent Packages

This directory contains **SKILL.md** files — the same protocols from the root directory, but formatted as drop-in packages for AI agent frameworks (Claude Code, Gemini, GPT, etc.).

## Structure

```
skills/
├── ghosty-collider/
│   └── SKILL.md        ← Ghost Extraction + Collision + Vision + Reality Bridge
├── precog-protocol/
│   └── SKILL.md        ← Signal Map + Convergence + Timing Grid + Action Window
└── berserk-mode/
    └── SKILL.md        ← LLM Creative Rage Protocol (8 phases + DRIFT)
```

## How to Use

### Claude Code / Antigravity / Gemini

Copy the skill directory into your agent's skills folder:

```bash
cp -r skills/ghosty-collider /path/to/your/.agent/skills/
cp -r skills/precog-protocol /path/to/your/.agent/skills/
cp -r skills/berserk-mode /path/to/your/.agent/skills/
```

### Other Agent Frameworks

Each `SKILL.md` has YAML frontmatter with:
- `name` — Skill identifier
- `description` — Trigger conditions and usage summary
- `metadata` — Author, version, theoretical basis

The body is the full protocol in markdown. Feed it to your agent as system context or tool documentation.

## Skills vs. Root-Level Docs

| | Root-level `.md` files | `/skills/SKILL.md` files |
|:--|:--|:--|
| **Audience** | Humans reading on GitHub | AI agents consuming as instructions |
| **Format** | Clean documentation, navigation links | YAML frontmatter + comprehensive instructions |
| **Content** | Same protocols, human-optimized | Same protocols, agent-optimized |
| **Internal refs** | Cross-links to other docs | Trigger conditions, auto-activation rules |

## License

Same as the root project: [CC BY-NC 4.0](../LICENSE)
