# UsefulPrompts

A curated collection of high-quality prompts from various creators across the internet.

## Structure

```
prompts/
├── Author Name/
│   ├── README.md           # Author bio, links, prompt index
│   ├── 001-Prompt-Name.md  # Individual prompts with metadata
│   ├── 002-Another-Prompt.md
│   └── ...
templates/
├── PROMPT_TEMPLATE.md      # Template for new prompts
└── AUTHOR_README_TEMPLATE.md
```

## Prompt Format

Each prompt uses YAML frontmatter for rich metadata and searchability:

```yaml
---
template_version: "1.0"

name: "Prompt Name"
id: "001"
author: "Author Name"
prompt_version: "1.0"
created: "YYYY-MM-DD"
updated: "YYYY-MM-DD"

tags:
  - ideation
  - optimization
category: "general"  # general | coding | writing | research | agents | system

description: |
  What this prompt achieves.
use_cases:
  - "Example use case"
example_input: "What to provide"
example_output: "What you get"

source_url: ""
license: "CC0"
---
```

## Finding Prompts

**By tag:** Search for tags like `ideation`, `optimization`, `debugging`, `agents`

**By category:** `general`, `coding`, `writing`, `research`, `agents`, `system`

**By author:** Browse `prompts/{Author Name}/README.md`

## Adding Prompts

1. Create author folder if new: `prompts/{Author Name}/`
2. Add author README using `templates/AUTHOR_README_TEMPLATE.md`
3. Add prompts using `templates/PROMPT_TEMPLATE.md`
4. Use format: `{NNN}-{Prompt-Name-In-Kebab-Case}.md`

## Authors

| Author | Prompts | Focus |
|--------|---------|-------|
| [Jeffrey Emanuel](./prompts/Jeffrey%20Emanuel/) | 4 | Agent optimization, codebase analysis |

## Tags Index

| Tag | Description |
|-----|-------------|
| `ideation` | Brainstorming and idea generation |
| `optimization` | Performance and efficiency improvements |
| `debugging` | Finding and fixing issues |
| `documentation` | README, docs, comments |
| `agents` | Agent-specific tooling and workflows |
| `architecture` | System design and structure |
| `refactoring` | Code improvement without behavior change |
| `analysis` | Deep investigation and understanding |
