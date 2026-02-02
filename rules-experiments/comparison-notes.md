# Rule Experiment Comparison & Findings

## Overview
I experimented with multiple rule variants to understand how different constraints affect AI agent behavior.

Each version optimized for a different goal: flexibility, planning, or correctness.

---

## v1 – Initial Rules
**Strengths**
- Lightweight and fast
- Good for simple questions

**Weaknesses**
- Inconsistent planning
- Occasional assumption drift

---

## v2 – Planning-Heavy
**Strengths**
- Strong alignment with user intent
- Clear reasoning and structure
- Fewer misinterpretations

**Weaknesses**
- Slightly slower interactions
- Overhead for simple tasks

---

## v3 – Verification-Focused
**Strengths**
- Highest reliability
- Reduced hallucinations
- Better handling of edge cases

**Weaknesses**
- Verbose
- Conservative for creative tasks

---

## Final Synthesis

The final rules file used in `.github/copilot-instructions.md` is a synthesis of:

- v2’s mandatory planning discipline
- v3’s verification-first mindset

This combination provided the best balance between correctness, clarity, and efficiency for my workflow.
