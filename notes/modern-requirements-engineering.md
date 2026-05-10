# Modern Requirements Engineering

## Summary

Modern requirements engineering has evolved from large monolithic specification documents to agile user stories and then to AI-native requirements.

In AI-native development, requirements are not only communication tools for humans. They become structured context for AI agents.

## Human-Agile vs AI-Native Requirements

Human developers can often infer missing context from domain knowledge and common sense.

AI agents behave differently:

- they interpret instructions literally,
- they only know the context provided to them,
- they may guess when requirements are vague,
- they may create invented APIs, fake libraries, or unnecessary architecture.

Therefore, requirements for AI should be explicit, bounded, and testable.

## Agile Requirements Hierarchy

A useful hierarchy is:

```text
Theme
└── Epic
    └── User Story
        └── Atomic Task
```

For AI agents, decomposition should continue until the task is small enough to fit into a clear prompt and be verified automatically.

## Standard User Story Format

```text
As a [Role],
I want to [Action],
so that [Value].
```

The role gives the AI context about the user.
The action defines the behavior to implement.
The value explains why the feature matters and prevents useless implementation.

## INVEST Principle

A good user story should be:

- Independent,
- Valuable,
- Small,
- Testable.

For AI-native development, `Small` and `Testable` are especially important because the AI must understand the story within its context window and verify its output.

## Acceptance Criteria

Acceptance Criteria define the boundary of done.

They should:

- remove subjective ambiguity,
- specify validation rules,
- include edge cases,
- state what not to do,
- guide AI-generated tests.

## BDD Format

BDD expresses behavior through Given / When / Then:

```gherkin
Given [initial context]
When [specific action]
Then [expected result]
```

This format is useful for AI because it transforms requirements into semi-structured logic.

## Context Injection

AI-ready requirements should reference the source of truth:

- architecture documents,
- style guides,
- existing files,
- data schemas,
- mock responses,
- known patterns.

## Key Rule

Write requirements for a brilliant intern who has amnesia every 10 minutes.

This means every requirement should contain enough local context to be safely implemented without hidden assumptions.

## Course Relevance

The practical assignment requires preparing AI-ready requirements for the course project. The focus is not only on writing user stories, but on turning them into precise contracts that guide AI agents.
