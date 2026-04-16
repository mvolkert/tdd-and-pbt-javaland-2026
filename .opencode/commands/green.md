---
description: Enter the Green phase of TDD - implement minimal code to make the test pass
agent: green
---

Use the `green` agent to run the Green phase of TDD.

Do NOT perform this phase manually. The agent enforces TDD discipline and prevents common mistakes.

**After Green completes**: You MUST launch a separate task with the `refactor` agent for the Refactor phase. Never combine Green+Refactor in one agent call.

Provide the agent with the necessary context:
- Test file path
- Failing test name and expected behavior
- Current error message
- Implementation file path
