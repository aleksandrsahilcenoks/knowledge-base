# ADR-001: Pattern-Based Feature Implementation

## Status

Draft

## Context

Practical Assignment 4 requires implementing the business logic of one selected feature from Assignment 3 using a suitable structural or behavioral design pattern.

The goal is to avoid unstructured spaghetti code and create an architectural harness for AI-assisted development.

## Decision

The exact pattern will be selected after the project feature is chosen.

Candidate patterns:

- Strategy, if the feature contains interchangeable business rules.
- Factory, if the feature creates different object types.
- Observer, if one event triggers multiple reactions.
- Command, if user actions should be encapsulated, logged, queued, or undone.
- Adapter, if the feature integrates with an external service.

## Consequences

The implementation should include:

- documented pattern choice,
- Mermaid class diagram,
- tests,
- clear separation of responsibilities,
- GitHub Issue and Pull Request.

## AI Harness Rule

AI must preserve the chosen pattern structure and must not collapse the implementation into one large function or conditional block.
