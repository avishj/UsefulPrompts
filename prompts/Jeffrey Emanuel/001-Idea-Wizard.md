---
template_version: "1.0"

name: "Idea Wizard"
id: "001"
author: "Jeffrey Emanuel"
prompt_version: "1.0"
created: "2025-01-16"
updated: "2025-01-16"

tags:
  - ideation
  - optimization
  - brainstorming
  - analysis

category: "general"

description: |
  Generates 30 improvement ideas for a project, then rigorously evaluates
  and winnows them down to the top 5 with detailed rationale. Useful for
  finding high-impact, pragmatic improvements.

use_cases:
  - "Project improvement brainstorming"
  - "Feature prioritization"
  - "Codebase enhancement planning"

example_input: "A project codebase or detailed description"
example_output: "Ranked list of 5 best improvement ideas with full rationale"

source_url: "https://x.com/doodlestein/status/2009501485483073866"
license: "unknown"
---

# Idea Wizard

> Generates 30 improvement ideas, then winnows to the top 5 with detailed rationale.

## Prompt

```
Come up with your very best ideas for improving this project to make it more robust, reliable, performant, intuitive, user-friendly, ergonomic, useful, compelling, etc. while still being obviously accretive and pragmatic. Come up with 30 ideas and then really think through each idea carefully, how it would work, how users are likely to perceive it, how we would implement it, etc; then winnow that list down to your VERY best 5 ideas. Explain each of the 5 ideas in order from best to worst and give your full, detailed rationale and justification for how and why it would make the project obviously better and why you're confident of that assessment. Use ultrathink.
```

## Usage Notes

- Best used after the agent has fully explored the codebase
- "ultrathink" triggers extended thinking mode in compatible models
- Works well with Claude's thinking modes or o1/o3 models
