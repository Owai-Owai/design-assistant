# Design Handoff & Documentation Sub-Skill

This sub-skill handles everything related to handing off designs to developers —
specs, annotations, redlines, communication, and implementation guidance.

---

## What This Sub-Skill Covers

- Writing design handoff notes and specs
- Documenting component measurements and spacing
- Writing developer-friendly design annotations
- Communicating design intent to engineers clearly
- Writing QA / design review checklists
- Responding to developer questions about designs
- Documenting responsive behaviour and breakpoints

---

## Output Formats

### Handoff Spec
```
Feature / Screen: [Name]
Designer: [Name]
Date: [Date]
Figma Link: [URL]

Overview:
  [Brief description of what this screen/feature does]

Components Used:
  - [Component name] — [Link to design system docs if available]

Spacing & Layout:
  - Outer padding: [value]
  - Inner spacing: [value]
  - Grid: [columns, gutter, margin]

Typography:
  - [Element]: [Font / Size / Weight / Line height / Color token]

Colors:
  - [Element]: [Token name or hex value]

Responsive Behaviour:
  - Desktop (1440px+): [Description]
  - Tablet (768px–1439px): [Description]
  - Mobile (< 768px): [Description]

Interactive States:
  - [State]: [Description of visual change]

Edge Cases & Empty States:
  - [Scenario]: [What to show]

Assets:
  - [Asset name]: [Export format / size / location]

Notes for Developers:
  - [Any implementation nuances, animation details, or gotchas]
```

### Design Annotation
```
[Element / Component]
→ [Clear instruction for the developer]
→ [Token or exact value]
→ [Behaviour note if interactive]
```

### Design QA Checklist
```
Screen / Feature: [Name]
Reviewed by: [Designer name]
Date: [Date]

Layout
  □ Spacing matches spec
  □ Grid alignment is correct
  □ Responsive breakpoints behave correctly

Typography
  □ Font sizes and weights match
  □ Line heights are correct
  □ Text truncation handled correctly

Color
  □ All colors match design tokens
  □ Contrast ratios meet WCAG AA

Interactions
  □ Hover states implemented
  □ Focus states visible for keyboard nav
  □ Loading and error states handled

Content
  □ Empty states designed and implemented
  □ Long content / edge cases handled

Accessibility
  □ Alt text on images
  □ ARIA labels where needed
  □ Tab order is logical
```

---

## Writing Guidelines

- Write for developers who haven't seen the design before
- Be explicit — never say "as shown in Figma" without also describing it in words
- Always include token names alongside raw values
- Call out interactive behaviour, animations, and transitions explicitly
- Highlight edge cases developers commonly miss (empty states, errors, long text)

---

## Example Triggers

- "Write a handoff spec for this screen"
- "Annotate these designs for the developer"
- "Create a design QA checklist"
- "Explain the responsive behaviour of this layout"
- "Write notes to send to the dev team about this component"
