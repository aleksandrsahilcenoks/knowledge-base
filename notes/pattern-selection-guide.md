# Pattern Selection Guide

This guide helps choose a design pattern for a feature from Practical Assignment 3.

## Strategy Pattern

Use Strategy when:

- the feature has several alternative algorithms,
- `if/else` or `switch` statements are growing,
- behavior should be selected at runtime,
- new rules may be added later.

Example:

```text
Different task-priority calculation strategies:
- deadline-based,
- effort-based,
- importance-based.
```

## Factory Pattern

Use Factory when:

- object creation is complex,
- the exact object type depends on input,
- creation logic should not be scattered across the codebase.

Example:

```text
Create different notification senders:
- EmailNotificationSender,
- TelegramNotificationSender,
- InAppNotificationSender.
```

## Observer Pattern

Use Observer when:

- one event should trigger several reactions,
- the subject should not know the concrete receivers,
- the system needs publish-subscribe behavior.

Example:

```text
When a task is completed:
- update progress statistics,
- send notification,
- write activity log.
```

## Command Pattern

Use Command when:

- user actions should be represented as objects,
- actions may need undo/redo,
- actions should be queued or logged.

Example:

```text
Task commands:
- CreateTaskCommand,
- CompleteTaskCommand,
- DeleteTaskCommand.
```

## Adapter Pattern

Use Adapter when:

- an external service has an incompatible interface,
- legacy code must be used with a new interface,
- third-party APIs should be hidden behind internal contracts.

Example:

```text
Adapt an external calendar API to the application's internal CalendarProvider interface.
```

## Builder Pattern

Use Builder when:

- an object has many optional fields,
- construction requires several steps,
- creation logic should be readable and safe.

Example:

```text
Build a complex StudyPlan object from goals, deadlines, tasks, and preferences.
```

## Singleton Pattern

Use Singleton only when exactly one object should coordinate actions across the system.

Use carefully because global state can reduce testability.

Example:

```text
ApplicationConfig.
```
