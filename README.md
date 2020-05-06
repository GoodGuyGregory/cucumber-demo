## Cucumber BDD

Written in Gherkin,
Which processes Examples of Tests as Scenarios. in this basic syntax


`Scenario` tells Cucumber we’re about to describe an example that it can execute.
`Given, When` and `Then` identify the steps of the scenario.

```gherkin
Scenario: Listener is within range
  Given Lucy is located 15m from Sean
  When Sean shouts "free bagels at Sean's"
  Then Lucy hears Sean’s message
```

**Given** is the context for the scenario. We’re putting the system into a specific state, ready for the scenario to unfold.

**When** is an action. Something that happens to the system that will cause something else to happen: an outcome.

**Then** is the outcome. It’s the behaviour we expect from the system when this action happens in this context.