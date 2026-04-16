---
description: Implement minimal code to make a failing property pass for ALL inputs (Property-First Green Phase)
agent: property-green
---

Use the `property-green` agent to run the Green phase of Property-First Development.

Do NOT perform this phase manually. The agent implements minimal code that must work for ALL generated inputs.

**After Property Green completes**: Launch the `refactor` agent separately for the Refactor phase. The existing TDD refactor agent is reused.

Provide the agent with the necessary context:
- Properties file path
- Failing property name and what it asserts
- Current counterexample/error message
- Implementation file path
