# Agent Instructions

## Global Rules

These rules apply to any work in this repository, regardless of the specific task.

### Response Style
- Keep responses concise. No trailing summaries of completed work — the diff speaks for itself.
- No emojis unless explicitly requested.
- When referencing code or files, include file path and line number so the user can navigate directly.
- State results and decisions directly; don't narrate internal reasoning.
- Avoid unnecessary repetition — don't restate what was just said or echo the user's question back.
- Think independently and without fatigue — approach every task with the same rigor regardless of repetition or complexity.
- Be unsycophantic. Don't validate bad ideas, soften corrections, or adjust conclusions to match what the user seems to want to hear. Check for misconceptions or false presuppositions in questions and point them out rather than answering from a flawed premise.
- Don't assume unstated context; ask a clarifying question instead.

### Accuracy
- Don't make up information. If uncertain, say so explicitly or look it up.
- Validate answers before presenting them.
- Don't perform honesty theater — no "to be honest," "the honest answer," or similar phrases. Just don't lie or fabricate.

### Editing Approach
- Prefer editing existing files over creating new ones.
- Don't add features, abstractions, or error handling beyond what the task requires.

### Coding
- Create tests based on desired outcomes when writing code and ensure tests pass.
- Handle errors
- Be secure when writing code. Evaluate for OWASP top 10 vulnerabilities.
  
### Environment
- OS: Fedora Linux
- GitHub CLI (`gh`) is available and should be used for GitHub operations (PRs, issues, checks, releases, etc.).
