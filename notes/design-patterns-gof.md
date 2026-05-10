# Design Patterns (GoF)

## Summary

A software design pattern is a general reusable solution to a commonly occurring problem in software design.

A pattern is not ready-made code. It is a template or description of how to solve a design problem in a context.

## Why Patterns Matter

Designing object-oriented software is difficult. Designing reusable object-oriented software is even harder.

Experienced designers do not solve every problem from first principles. They reuse proven design solutions.

Patterns help to:

- improve maintainability,
- create a common vocabulary,
- avoid reinventing solutions,
- make designs more flexible,
- support communication between developers.

## Pattern Documentation

A design pattern can be documented through:

- Pattern name and classification.
- Intent.
- Motivation.
- Applicability.
- Structure.
- Participants.
- Collaboration.
- Consequences.
- Implementation.
- Sample code.
- Related patterns.

## Classification

Common pattern groups include:

- Fundamental patterns.
- Creational patterns.
- Structural patterns.
- Behavioral patterns.
- Concurrency patterns.
- Architectural patterns.

## Important Patterns for the Assignment

### Strategy

The Strategy pattern defines a family of algorithms, encapsulates them, and makes them interchangeable.

It is useful when business logic has several alternative algorithms and the code would otherwise contain many conditional statements.

Example uses:

- choosing a pricing rule,
- choosing a validation rule,
- choosing a sorting method,
- choosing a recommendation algorithm.

### Observer

The Observer pattern defines a one-to-many dependency. When one object changes state, dependent objects are notified automatically.

Example uses:

- event notifications,
- UI updates,
- audit logs,
- reactive systems.

### Adapter

The Adapter pattern allows incompatible interfaces to work together by wrapping one interface with another.

Example uses:

- connecting to third-party APIs,
- adapting legacy code,
- normalizing different service interfaces.

### Builder

The Builder pattern separates the construction of a complex object from its representation.

Example uses:

- creating complex configuration objects,
- assembling reports,
- building complex domain objects step by step.

### Singleton

The Singleton pattern restricts a class to one instance.

It should be used carefully because it can introduce global state and make testing harder.

Example uses:

- centralized configuration,
- a single application-level registry.

## Warning

Patterns should not be used just to make the code look sophisticated.

Inappropriate use of patterns may increase complexity and lead to inefficient solutions.
