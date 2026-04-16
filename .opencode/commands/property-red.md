---
description: Activate one property, predict failure, verify it fails (Property-First Red Phase)
agent: property-red
---

Use the `property-red` agent to run the Red phase of Property-First Development.

Do NOT perform this phase manually. The agent activates one property, makes predictions, and verifies failure.

Provide the agent with the necessary context:
- Properties file path
- Which `@Disabled("todo")` property to activate (name or line number)
- Current number of passing properties
- Implementation file path
