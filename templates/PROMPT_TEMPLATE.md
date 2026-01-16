---
# Prompt Metadata (YAML Frontmatter)
name: "Prompt Name"
id: "001"  # Sequential ID within author's folder
author: "Author Name"  # Must match parent folder name
version: "1.0"
created: "YYYY-MM-DD"
updated: "YYYY-MM-DD"

# Categorization
tags:
  - ideation
  - optimization
  - code-review
  # Add relevant tags from: ideation, optimization, code-review, debugging,
  # refactoring, architecture, testing, documentation, planning, analysis,
  # creative, productivity, agents, system-prompts, personas, etc.

category: "general"  # general | coding | writing | research | agents | system

# Compatibility & Requirements
models:
  - claude-sonnet
  - claude-opus
  - gpt-4
  # List models this prompt works well with
requires_thinking: false  # true if prompt needs extended thinking/reasoning
context_size: "small"  # small (<2k) | medium (2-8k) | large (8k+)

# Discovery
description: |
  One-paragraph description of what this prompt achieves
  and when you'd want to use it.
use_cases:
  - "Generating improvement ideas for a project"
  - "Brainstorming session kickoff"
example_input: "A codebase or project description"
example_output: "Ranked list of improvement ideas with rationale"

# Source & Attribution
source_url: ""  # Original URL where prompt was found (if applicable)
license: "CC0"  # CC0 | MIT | CC-BY | unknown
---

# {{ name }}

> {{ description }}

## Prompt

```
Paste the actual prompt text here.
Use triple backticks to preserve formatting.
```

## Usage Notes

Any tips, variations, or context for getting the best results.

## Variations

Optional section for alternative versions or modifications.
