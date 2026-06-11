# Sample Project Document Stack

This example shows a public-facing structure for a project document stack organized according to PACE.

## Purpose

PACE uses documents as operating infrastructure. The stack separates canonical truth, dynamic state, and audit surfaces so work remains legible across sessions.

## Sanitized Example

```text
project-root/
  README.md

  project-status/
    current-status.md
    milestone-status.md
    open-risks.md

  planning/
    product-spec.md
    architecture-review.md
    milestone-plan.md

  tasks/
    task-001-public-slice.md
    task-002-public-slice.md

  audit/
    cross-audit-notes.md
    review-findings.md
    closure-checklist.md

  handoff/
    session-summary.md
    next-session-start.md
```

## Role Separation

- `planning/` holds intent, constraints, and reviewed delivery shape.
- `project-status/` reflects current operational truth.
- `tasks/` contains bounded execution slices.
- `audit/` captures critique and verification.
- `handoff/` preserves continuity between sessions.

## Why This Matters

The structure makes it harder for plans, status, and review state to collapse into one blurry surface. That separation is one of the practical strengths of the method.
