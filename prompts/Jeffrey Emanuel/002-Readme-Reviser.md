---
template_version: "1.0"

name: "Readme Reviser"
id: "002"
author: "Jeffrey Emanuel"
prompt_version: "1.0"
created: "2025-01-16"
updated: "2025-01-16"

tags:
  - documentation
  - maintenance
  - readme

category: "coding"

description: |
  Systematically updates README documentation to reflect recent code changes,
  finds undocumented features, and expands coverage of algorithms, design
  principles, and functionality.

use_cases:
  - "Post-development documentation sync"
  - "README expansion and improvement"
  - "Finding undocumented features"

example_input: "A project with outdated README"
example_output: "Comprehensive README updates covering all implemented features"

source_url: "https://x.com/doodlestein/status/2009505210557710478"
license: "unknown"
---

# Readme Reviser

> Updates README to reflect code changes and finds undocumented features.

## Prompt

```
OK, we have made tons of recent changes that aren't yet reflected in the README file. First, reread AGENTS dot md so it's still fresh in your mind. Use ultrathink. Now, we need to revise the README for these changes (don't write about them as 'changes' however, make it read like it was always like that, since we don't have any users yet!).

Also, what else can we put in there to make the README longer and more detailed about what we built, why it's useful, how it works, the algorithms/design principles used, etc? This should be incremental NEW content, not replacement for what is there already. 

And generally, look for any chunks of important features/functionality that are currently fully implemented in the code, but unmentioned, under-documented, under-explained, or under-justified in the README file.
```

## Usage Notes

- Assumes AGENTS.md exists with project context
- Instructs agent to write as evergreen docs, not changelog
- Good for pre-launch documentation polish
