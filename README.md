# handwritten

An agent skill that turns any topic into a handwritten-style notebook page: ruled paper, pen-and-highlighter look, hand-drawn labelled diagrams, boxed key points and a sticky-note exam tip.

## Install

Clone this repo into your agent's skills folder. The folder name must be `handwritten`.

**Claude Code, for all projects (macOS, Linux, Git Bash on Windows):**

```bash
git clone https://github.com/Charikshith/handwritten.git ~/.claude/skills/handwritten
```

**Claude Code, for one project (run from the project root):**

```bash
git clone https://github.com/Charikshith/handwritten.git .claude/skills/handwritten
```

**Other agents that read `.agents/skills/` (Codex and similar):**

```bash
git clone https://github.com/Charikshith/handwritten.git .agents/skills/handwritten
```

**Windows PowerShell, Claude Code, all projects:**

```powershell
git clone https://github.com/Charikshith/handwritten.git "$HOME\.claude\skills\handwritten"
```

Restart the agent session so it picks up the new skill. To update later, run `git pull` inside the skill folder.

## Use

Type `/handwritten <topic>`, or ask for handwritten notes, study notes or revision notes. The skill writes a self-contained HTML page you can open in a browser.

## Examples

- [`examples/photosynthesis.html`](examples/photosynthesis.html): notes made with `/handwritten photosynthesis`.
- [`examples/python-list-comprehensions-notes.html`](examples/python-list-comprehensions-notes.html): Python notes with syntax-coloured code blocks, made with `/handwritten Python list comprehensions`.

Download a page and open it in a browser.

Pulled from [Charikshith/Skills](https://github.com/Charikshith/Skills).
