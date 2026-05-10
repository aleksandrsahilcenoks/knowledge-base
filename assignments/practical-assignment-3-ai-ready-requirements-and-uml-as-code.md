# Practical Assignment 3: AI-Ready Requirements and UML-as-Code

## Assignment Name

Practical Assignment 3 (2025–2026): AI-Ready Requirements and UML-as-Code

## Opened

2026-04-09

## Main Idea

AI agents do not have human common sense and cannot infer hidden intent from vague requirements. Therefore, an AI-native engineer should manage AI work through explicit contracts:

- deeply decomposed requirements,
- Behavior-Driven Development acceptance criteria,
- Mermaid.js diagrams as UML-as-code,
- pure functions with clear inputs and outputs.

## Why This Matters

A vague task such as `Create a shopping cart` can lead to hallucinated libraries, hidden side effects, inconsistent architecture, and technical debt.

A better requirement should specify:

- the actor,
- the goal,
- the business value,
- constraints,
- BDD scenarios,
- affected files,
- expected inputs and outputs,
- edge cases,
- diagrammed logic,
- testing expectations.

## Expected Deliverables

For my course project, I should prepare at least three atomic stories in AI-native format.

Each atomic story should contain:

1. User Story.
2. Context and references.
3. Constraints.
4. Acceptance Criteria in BDD format.
5. Mermaid.js diagram.
6. Pure function contract, where applicable.
7. Testing notes.

## Suggested Repository Location

In the project repository:

```text
docs/
├── requirements/
│   ├── epic-overview.md
│   ├── story-001.md
│   ├── story-002.md
│   └── story-003.md
├── diagrams/
│   ├── use-case.md
│   ├── activity-flow.md
│   └── sequence-flow.md
└── pure-functions.md
```

In this knowledge base repository:

```text
assignments/
└── practical-assignment-3-ai-ready-requirements-and-uml-as-code.md

notes/
├── modern-requirements-engineering.md
└── uml-as-code.md

templates/
├── ai-native-user-story-template.md
├── bdd-scenario-template.md
└── mermaid-uml-template.md
```

## Checklist

- [ ] Choose the course project theme.
- [ ] Define one epic.
- [ ] Decompose the epic into at least three atomic user stories.
- [ ] Write BDD acceptance criteria for each story.
- [ ] Add at least one Mermaid diagram.
- [ ] Define pure-function contracts for logic-heavy tasks.
- [ ] Create GitHub Issues for stories.
- [ ] Link implementation Pull Requests to Issues.
