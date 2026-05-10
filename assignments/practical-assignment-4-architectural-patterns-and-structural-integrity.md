# Practical Assignment 4: Architectural Patterns and Structural Integrity

## Assignment Name

Practical Assignment 4 (2025–2026): Architectural Patterns and Structural Integrity

## Opened

2026-04-24

## Main Idea

The goal of this assignment is to move from isolated functions to structured modules.

Instead of writing code that only "works", the feature should be designed so that it remains:

- extensible,
- maintainable,
- testable,
- understandable,
- safe for AI-assisted development.

## Task Objective

Implement the business logic of one selected feature from Practical Assignment 3 by applying a suitable structural or behavioral design pattern.

Possible patterns:

- Strategy,
- Factory,
- Observer,
- Command,
- Singleton,
- Adapter,
- Builder,
- MVC,
- Proxy.

## Why This Matters for AI-Native Development

AI agents may generate procedural, tangled, or duplicated code if the architectural boundaries are not explicit.

A design pattern provides a strict architectural harness:

- it defines roles,
- separates responsibilities,
- reduces uncontrolled dependencies,
- makes extension points explicit,
- gives the AI a known design vocabulary.

## Expected Deliverables

For the selected feature, I should provide:

1. Selected feature from Assignment 3.
2. Chosen design pattern.
3. Explanation of why this pattern fits the problem.
4. UML/Mermaid class diagram.
5. Implementation of business logic.
6. Tests for the pattern-based logic.
7. Short reflection on consequences and trade-offs.

## Recommended Project Repository Structure

```text
docs/
├── architecture/
│   ├── design-pattern-choice.md
│   └── selected-feature-pattern.md
├── diagrams/
│   └── selected-feature-class-diagram.md
└── decisions/
    └── adr-001-use-strategy-pattern.md

src/
└── features/
    └── selected-feature/
        ├── domain/
        ├── strategies/
        ├── services/
        └── tests/
```

## Assignment Checklist

- [ ] Select one atomic story from Assignment 3.
- [ ] Identify the unstable or variable part of the business logic.
- [ ] Choose a suitable design pattern.
- [ ] Explain pattern intent and applicability.
- [ ] Create a Mermaid class diagram.
- [ ] Implement the business logic using the pattern.
- [ ] Add tests.
- [ ] Link GitHub Issue to Pull Request.
- [ ] Document consequences and trade-offs.
