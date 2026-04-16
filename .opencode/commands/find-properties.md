---
description: Find properties to harden an existing TDD implementation with property-based tests
agent: find-properties
---

Use the `find-properties` agent to find properties for property-based testing.

Do NOT perform this phase manually. The agent systematically analyzes the implementation and discovers meaningful properties.

Provide the agent with the necessary context:
- Implementation file path
- Test file path (existing TDD tests)
- Target properties file path (e.g., `*Properties.java`)
