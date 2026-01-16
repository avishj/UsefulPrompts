---
name: "Robot-Mode Maker"
id: "003"
author: "Jeffrey Emanuel"
version: "1.0"
created: "2025-01-16"
updated: "2025-01-16"

tags:
  - agents
  - cli
  - tooling
  - api-design

category: "coding"

models:
  - claude-sonnet
  - claude-opus
  - gpt-4
requires_thinking: true
context_size: "large"

description: |
  Creates agent-optimized CLI interfaces that mirror UI functionality
  but output JSON/markdown for token efficiency. Designs tooling that
  coding agents would want to use themselves.

use_cases:
  - "Building agent-friendly CLIs"
  - "Adding programmatic interfaces to UI-first apps"
  - "Optimizing tools for LLM consumption"

example_input: "An application with UI but no CLI"
example_output: "Agent-optimized CLI with JSON/markdown output"

source_url: "https://x.com/doodlestein/status/2009507330598043962"
license: "unknown"
---

# Robot-Mode Maker

> Creates agent-optimized CLI interfaces with JSON/markdown output.

## Prompt

```
Next, I want you to create a "robot mode" for coding agents that want to interact with this so they don't need to use the UI but can instead access all the same functionality via a cli in the console that is hyper-optimized and ergonomic for agents, while also being ultra-intuitive for coding agents like yourself; the agent users should get back as output either json or markdown-- whatever fits best in the context and is most token-efficient and intuitive for you. 

Basically, the agent users should get all the same information as a human would get from manipulating and visually observing the UI, but in a more usable, helpful, intuitive, and accessible form for agents. Make the tooling here that YOU would want if YOU were using it (because you WILL be!), that maximizes agent ergonomics and agent intuition. Be sure to give the command a quick-start mode (when no arguments are supplied) that explains the most critical functionality in the most intuitive, token-dense way possible. Use ultrathink.
```

## Usage Notes

- Leverages the agent's self-interest ("you WILL be using this")
- Emphasizes token efficiency for agent consumption
- Quick-start mode provides self-documenting behavior
