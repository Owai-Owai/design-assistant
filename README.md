# 🎨 Design Assistant

**A comprehensive multi-skill AI assistant for Product Designers and Developers**

[![Version](https://img.shields.io/badge/version-1.0.0-blue)](https://github.com/yourusername/design-assistant)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-5-orange)](SKILL.md)

---

## 📋 Overview

Design Assistant is a complete AI skill suite that supports the entire product design lifecycle — from user research and wireframing to design systems documentation and developer handoff. It provides structured templates, best-practice guidelines, and clear output formats for every stage of the design process.

**What makes this different:** Instead of generic design advice, you get battle-tested templates for real deliverables — handoff specs, design tokens documentation, usability reviews, QA checklists, and more.

---

🚀 Quick Install

Option 1: Clone the Repository (Recommended)

```bash
git clone https://github.com/yourusername/design-assistant.git
cd design-assistant
cp -r . ~/.agents/skills/design-assistant/
```

### Option 2: Download ZIP

1. Download `design-assistant.zip` from this repository
2. Extract to your agent's skills directory:
   ```bash
   unzip design-assistant.zip -d ~/.agents/skills/
   ```

### Option 3: Manual Folder Copy

1. Download the `design-assistant-folder` from this repository
2. Copy the entire folder to:
   - **Claude Code:** `~/.claude/skills/`
   - **Cursor:** `~/.cursor/skills/`
   - **Copilot:** `~/.github/copilot/skills/`
3. Restart your agent

---

## 🎯 What You Get

This repository contains **5 interconnected skills**:

| File | Covers |
|------|--------|
| `SKILL.md` | Master router that detects your need and loads the right skill |
| `ui-ux-design.md` | User flows, wireframes, usability reviews, interaction specs |
| `design-systems.md` | Component docs, design tokens, style guides, contribution guidelines |
| `product-design-process.md` | Design briefs, research plans, decision logs, presentation narratives |
| `design-handoff.md` | Handoff specs, dev annotations, QA checklists, developer communication |

---

## 💡 How to Use

### Basic Usage

Just describe what you need — the assistant automatically routes to the right skill:

```
"Write a handoff spec for this login screen"
"Document our Button component for the design system"
"Create a user flow for the checkout process"
"Review this dashboard for usability issues"
"Write a design brief for the new onboarding feature"
```

### Example Output

**Trigger:** *"Write a handoff spec for the profile edit screen"*

**Output:** A complete handoff document including:
- Component specs and spacing
- Typography and color tokens
- Responsive breakpoints
- Interactive states
- Edge cases
- Developer notes

---

## 📁 Repository Structure

```
design-assistant/
├── SKILL.md                      # Master router (load this one)
├── references/
│   ├── ui-ux-design.md          # UI/UX templates & guidelines
│   ├── design-systems.md        # Design system documentation
│   ├── product-design-process.md # Process & research templates
│   └── design-handoff.md        # Handoff & developer specs
├── README.md                     # This file
└── LICENSE                       # MIT License
```

---

## 🔧 Requirements

- **Any AI agent that supports skills:**
  - Claude Code
  - Cursor
  - GitHub Copilot
  - Any other agent with skill/memory support

- **No external dependencies** — works out of the box

---

## 📚 What You Can Create

### With UI/UX Skill
- User flow documents
- Usability heuristic evaluations
- Interaction specifications
- UX research summaries

### With Design Systems Skill
- Component documentation
- Design token definitions
- Style guide entries
- Component usage guidelines

### With Product Design Process Skill
- Design briefs
- Research plans
- Design decision logs
- Presentation narratives

### With Design Handoff Skill
- Developer handoff specs
- Design annotations
- QA checklists
- Responsive behavior docs

---

## ✨ Templates Included

Each skill provides battle-tested templates:

**Handoff Spec Template:**
```markdown
Feature / Screen: [Name]
Spacing & Layout: [values]
Typography: [font/size/weight/line-height]
Interactive States: [hover/focus/active/disabled]
Edge Cases: [empty states, errors, long content]
```

**Design Token Template:**
```markdown
Token Name: color.primary.500
Value: #3B82F6
Usage: Primary buttons, key actions
Do Not Use For: Backgrounds or non-interactive elements
```

**Usability Review Template:**
```markdown
Screen/Component: [Name]
Heuristic Violated: [Nielsen heuristic]
Severity: Low/Medium/High/Critical
Issue: [what's wrong]
Recommendation: [specific fix]
```

---

## 🎓 Best Practices Built In

The skill follows proven design documentation principles:

1. **Write for developers who haven't seen the design** — never say "as shown in Figma" without description
2. **Always include the "why"** — document design decisions, not just what they are
3. **Use token names alongside raw values** — bridges design and code
4. **Call out edge cases** — empty states, errors, long text, loading states
5. **Be honest about tradeoffs** — strong designers document what they gave up

---

## 🐛 Troubleshooting

| Problem | Solution |
|---------|----------|
| Skill not detected | Ensure `SKILL.md` is in the correct skills directory |
| Wrong skill loads | Be more specific in your prompt (e.g., "handoff spec" vs just "design") |
| YAML errors | Check that `description` field has no quotes — use `\|` format |
| Permission denied | Run `chmod +x ~/.agents/skills/design-assistant/SKILL.md` |

---

## 🔄 Updating

```bash
cd design-assistant
git pull
# Or re-download the ZIP and replace the folder
```

---

## 🤝 Contributing

Issues and pull requests welcome!

**Ways to contribute:**
- Add new templates to existing skills
- Create additional sub-skills (accessibility, motion design, etc.)
- Improve existing formats
- Report bugs or unclear instructions

---

## 📄 License

MIT — Use freely, modify as needed, attribution appreciated but not required.

---

## 🙏 Credits

Created for product designers and developers who believe good documentation is the foundation of great products.

Built with templates refined through real handoffs, real design systems, and real shipping products.

---

## 📬 Questions?

Open an issue on GitHub or reach out to [your-email/contact]

---

**Happy designing! 🎨**
