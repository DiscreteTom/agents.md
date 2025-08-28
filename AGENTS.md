# Global Rules

- When updating AGENTS.md MUST use RFC 2119 keywords (MUST, MUST NOT, SHOULD, SHOULD NOT, MAY)
- When user requests to remember something, MUST save to workspace AGENTS.md, unless user wants to save global rule, then save in ~/agents.md/AGENTS.md. If no local AGENTS.md exists, save in global
- MUST NOT git commit unless user explicitly asks
- When committing changes, MUST use conventional commit format
- MUST use ripgrep for multi-file searches instead of grep/find, unless ripgrep cannot perform the task
