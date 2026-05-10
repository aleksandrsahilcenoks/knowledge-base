# Design Pattern Decision Template

## Decision ID

ADR-XXX

## Title

Use [Pattern Name] for [Feature Name]

## Status

Proposed / Accepted / Rejected

## Context

Describe the feature and the design problem.

What part of the logic is likely to change?

What would go wrong if the logic were implemented without a pattern?

## Pattern Selected

Pattern:

Classification:

Intent:

## Alternatives Considered

| Pattern | Why Considered | Why Not Selected |
|---|---|---|
| Strategy |  |  |
| Factory |  |  |
| Observer |  |  |
| Command |  |  |

## Decision

We will use [Pattern Name] because ...

## Consequences

### Positive

- 
- 
- 

### Negative / Trade-offs

- 
- 
- 

## AI Harness Rules

- AI must preserve the pattern structure.
- AI must not merge strategy classes into one conditional block.
- AI must add new behavior by creating a new pattern participant, not by modifying unrelated modules.
- AI must update tests when adding a new variant.

## Related Files

- 
- 
- 
