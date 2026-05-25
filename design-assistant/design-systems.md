# Design Systems Sub-Skill

This sub-skill handles design system documentation, component libraries,
design tokens, style guides, and anything related to building or maintaining
a consistent design language.

---

## What This Sub-Skill Covers

- Writing component documentation
- Defining and documenting design tokens
- Creating style guide entries (typography, color, spacing, iconography)
- Writing usage guidelines and do/don't examples
- Documenting component variants and states
- Writing contribution guidelines for a design system

---

## Output Formats

### Component Documentation
```
Component: [Name]
Description: [What it is and what problem it solves]

Usage:
  - Use when: [Specific contexts]
  - Don't use when: [Anti-patterns]

Variants:
  - [Variant Name]: [Description]

Props / Properties:
  - [Property]: [Type] — [Description] — Default: [value]

States: Default | Hover | Focus | Active | Disabled | Error

Accessibility:
  - [ARIA roles, keyboard nav, contrast requirements]

Examples:
  - [Example 1 description]
  - [Example 2 description]
```

### Design Token Entry
```
Token Name: [e.g. color.primary.500]
Value: [e.g. #3B82F6]
Usage: [Where and when to use this token]
Do Not Use For: [Anti-patterns]
Aliases: [Other names this token maps to]
```

### Style Guide Entry
```
Category: [Typography / Color / Spacing / Iconography]
Name: [e.g. Heading 1, Brand Blue, Space 4]
Value: [Actual value]
When to use: [Guidance]
Example: [Brief visual or textual example]
```

---

## Writing Guidelines

- Always explain the **why** behind design decisions, not just the what
- Include clear do/don't examples for every component
- Use precise language — "use for primary actions" not "use when needed"
- Document accessibility requirements for every component
- Keep token names semantic (e.g. `color.feedback.error` not `color.red`)

---

## Example Triggers

- "Write documentation for a Button component"
- "Define our color tokens"
- "Create a style guide entry for typography"
- "Document when to use a Modal vs a Drawer"
- "Write contribution guidelines for our design system"
