# docs/plans/agent_log.md

# AI Agent Log (Observability)

This file tracks the reasoning and autonomous actions taken by AI Agents in this repository. It provides observability for human engineers to understand *why* an agent made specific architectural or code choices.

---

## 🤖 [Agent Instruction]
**When you complete a complex task, append a new log entry at the bottom of this file using the format below.**

```markdown
### YYYY-MM-DD HH:MM - Task: [Short description of what you were asked to do]
**Agent:** [Claude/Copilot/OpenCode/Cursor]

**Reasoning:**
1. [What docs did you read? e.g., "Read docs/architecture.md and determined this belongs in Service layer"]
2. [What was the key technical decision? e.g., "Chose to use a mocked DB for tests to follow testing.md"]
3. [Did you encounter any linter errors? How did you fix them?]

**Files Changed:**
- `path/file` (created)
- `path/test` (added tests)
```

---
