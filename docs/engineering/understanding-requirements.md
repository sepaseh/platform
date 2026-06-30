# Candidate Document Summary

## Working Title

Understanding Requirements

## Why this document exists

Requirements are often confused with ideas, implementation tasks, technical preferences, and design decisions.

Before discussing how to analyze requirements, engineers must first understand what a requirement actually is.

---

## Key Conclusions

### A requirement is not a solution.

A requirement describes something that must be satisfied.

It should not dictate how the software will satisfy it.

If multiple valid designs can satisfy the same statement, it is likely still a requirement.

If the statement already assumes a particular implementation, it has probably entered the design phase.

---

### Requirements emerge from understanding the problem.

They are not limited to business requests.

A requirement may be discovered through:

- Business goals
- Operational constraints
- Technical limitations
- Cost considerations
- Security concerns
- Legal or regulatory obligations
- Engineering analysis

Business is one source of requirements, not the only one.

---

### Design exists to satisfy requirements.

Requirements define the expectations and constraints.

Design explores different ways to satisfy them.

A good design may completely change the workflow while still satisfying exactly the same requirements.

---

### A requirement should survive criticism.

Instead of defending every proposed requirement, engineers should challenge it.

Questions worth asking include:

- What happens if we remove it?
- What business objective does it protect?
- Is this really a requirement, or simply the first solution that came to mind?
- Can another design satisfy the same objective?

Requirements become stronger by surviving these challenges.

---

### Not everything discussed in meetings is a requirement.

Examples include:

- Technology preferences
- Framework choices
- Developer interests
- Trend-driven ideas
- Implementation tasks
- Design proposals

For example, "We should build a Form Builder" is not necessarily a requirement.

The real requirement might instead be:

"The business should be able to modify forms without requiring a new software release."

The Form Builder is only one possible design.

---

### Requirements are not all equally important.

Every requirement does not have the same priority.

Some are essential for the product to exist.

Others may be postponed to later releases.

Postponing a requirement does not change its nature; it only changes when it will be satisfied.

---

## Practical Engineering Mindset

Whenever someone proposes a solution, ask one simple question:

> If we do not implement this, which requirement will no longer be satisfied?

If there is no clear answer, the discussion is probably about design rather than requirements.
