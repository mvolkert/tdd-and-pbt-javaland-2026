---
description: Implement one @Disabled property-based test and analyze jqwik results
agent: implement-properties
---

Use the `implement-properties` agent to implement one property-based test at a time.

Do NOT perform this phase manually. The agent implements one property at a time and analyzes jqwik's results including counterexamples.

Provide the agent with the necessary context:
- Properties file path (e.g., `*Properties.java`)
- Which `@Disabled("todo")` property to implement (name or line number)
- Implementation file path
- Current number of passing properties
