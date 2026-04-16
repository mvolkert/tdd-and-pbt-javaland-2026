---
description: Refactor code using Simple Design Rules and Absolute Priority Premise
agent: refactor
---

Use the `refactor` agent to run the Refactor phase of TDD.

Do NOT perform this phase manually. The agent enforces TDD discipline and prevents common mistakes.

**This must be a separate agent call.** After each Green phase, explicitly invoke the Refactor agent — never combine Green+Refactor into one task.

Provide the agent with the necessary context:
- Test file path
- Implementation file path
- Current number of passing tests
- Recent changes made in Green phase
