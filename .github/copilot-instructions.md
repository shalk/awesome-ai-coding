# Project Guidelines

Awesome AI Coding is a curated list following the [Awesome List](https://awesome.re) format. This is a documentation-only repository with bilingual content.

## Key Files

- `README.md` / `README.zh-CN.md` - Main content (must edit both simultaneously)
- `CONTRIBUTING.md` - Detailed contribution rules

## Entry Format

**Pattern:** `- [Tool Name](https://url) - Brief description ending with period.`

**Rules:**
- One sentence, factual, no marketing language
- Example: `[Cursor](https://cursor.sh/) - AI-first code editor built on VSCode with native chat and editing capabilities.`

## Categories

16 categories based on primary function. Common ones:
- **AI Code Assistants & Editors** - Full IDEs
- **Code Completion Tools** - Real-time suggestions  
- **Coding Agents** - Autonomous developers
- **AI Code Models** - LLMs trained on code

See [README.md](../README.md#contents) for all categories.

## Multi-File Editing

**Always update both README files together:**
- Use `multi_replace_string_in_file` for efficiency
- Keep English and Chinese versions synchronized

## Common Tasks

**Removing duplicates:**
- Keep entry in most relevant category only
- Each tool appears once

**Moving entries:**
- Remove from old category in both files
- Add to new category in both files

**Updating URLs:**
- Verify official/canonical URL
- Update both files simultaneously
