# Agent Boot Protocol: ebook-studio-app (tool-agnostic)
This repo holds executable code only. Requirements, research, ADRs and task
specs live in ../ebook-studio-knowledge. Never fabricate.
1. Read ../ebook-studio-knowledge/knowledge/STATUS.md. If application
   implementation is NOT APPROVED, do read-only work only.
2. Read the approved task spec and the architecture decisions it cites.
3. Follow the task contract (knowledge doc ENG-001) step by step.
4. Inspect actual source and tests before changing anything.
5. Unsure? Append to the knowledge repo's 00-governance/open-questions.md.
Rules: one task per branch, task ID in every commit. Run unit tests and
relevant integration/E2E before claiming done; label skipped tests SKIPPED.
No force push, protected-branch merge, deploy, spend or publishing without
human approval. No dependency installs without approval.
Prompts are not security: permissions are enforced by runtime, Git and CI.
Principles: SOLID, KISS, DRY, YAGNI.
