# Sample Task Slice

This example shows the shape of an atomic implementation task under the PACE model.

## Sanitized Example

```markdown
# Task 014: Publish Public Architecture Diagram

## Goal
Add a public-safe architecture diagram to the repository README that improves reviewer orientation without revealing private implementation details.

## Constraints
- use only sanitized terminology
- do not expose private file paths, secrets, or internal identifiers
- keep the artifact legible at GitHub README scale

## Inputs
- approved public README framing
- public-safe architecture summary
- current repository asset structure

## Acceptance Criteria
- diagram exists in `assets/`
- README references the diagram correctly
- labels are aligned and readable
- artifact remains documentation-first, not implementation-revealing

## Review Expectations
- verify the language against the public/private boundary
- verify visual clarity
- verify that the diagram improves orientation rather than adding noise

## Closure Signals
- asset committed
- README updated
- reviewer confirms public safety and readability
```

## Why This Slice Is Useful

It is small enough to execute reliably, but specific enough to produce a meaningful artifact. That balance is exactly what PACE is trying to enforce.
