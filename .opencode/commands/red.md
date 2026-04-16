---
description: Enter the Red phase of TDD - create a failing test, make prediction, verify test fails
agent: red
---

Use the `red` agent to run the Red phase of TDD.

Do NOT perform this phase manually. The agent enforces TDD discipline and prevents common mistakes.

Provide the agent with the necessary context:
- Test file path
- Which `@Disabled("todo")` to activate
- Current number of passing tests
- Implementation file path
