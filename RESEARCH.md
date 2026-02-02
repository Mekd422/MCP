# External Research on AI Agent Rules

## 1. Boris Cherny – Claude Code Workflow
Source: https://x.com/bcherny/status/2007179832300581177

Key ideas extracted:
- Treat rules as a contract, not a prompt
- Enforce planning before execution
- Bias the agent toward small, reversible steps
- Prefer explicit verification over confidence

How I applied this:
- Added mandatory planning and confirmation steps
- Required verification strategy in every response

---

## 2. Cursor Agent Rules Best Practices
Source: Cursor documentation / community discussions

Key ideas:
- Rules should constrain behavior, not content
- Explicit “do not assume” instructions reduce hallucinations
- Iterative refinement of rules improves alignment

How I applied this:
- Added explicit constraints on assumptions
- Introduced clarification checkpoints

---

## 3. GitHub Copilot Instruction Patterns
Source: GitHub Copilot documentation & examples

Key ideas:
- Copilot respects concise, structured instructions best
- Markdown headings improve rule parsing
- Clear priority ordering prevents conflicts

How I applied this:
- Structured rules with headings
- Preserved mandatory Tenx trigger rules at top
