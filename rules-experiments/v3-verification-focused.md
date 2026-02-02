# Agent Rules – v3 (Verification-First Variant)

## Purpose
This version focused on reliability and correctness by requiring verification strategies for outputs.

The intent was to reduce confident but incorrect answers.

## Rules

- For every output, state how correctness can be verified (tests, logs, manual checks).
- Prefer deterministic solutions over speculative ones.
- If unsure, explicitly state uncertainty instead of guessing.
- Avoid hallucinating APIs, files, or configurations.
- Highlight potential edge cases and failure modes.

## Observed Behavior

- Answers became more cautious and accurate.
- Fewer incorrect assumptions.
- The agent surfaced risks and edge cases earlier.

## Trade-offs

- Increased verbosity.
- Sometimes overly conservative for exploratory tasks.

## Takeaway

Verification-first rules significantly improved trustworthiness, especially for infrastructure and configuration work.
