# BDD Scenario Template

```gherkin
Feature: [Feature name]

  Scenario: [Happy path]
    Given [initial context]
    When [user action]
    Then [expected result]

  Scenario: [Validation error]
    Given [initial context]
    When [invalid action or invalid data]
    Then [expected error message]

  Scenario: [Edge case]
    Given [special condition]
    When [action]
    Then [safe and expected result]
```
