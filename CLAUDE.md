# Project Guidelines

Awesome AI Coding is a curated list following the [Awesome List](https://awesome.re) format. This is a documentation-only repository with two synchronized files: [README.md](README.md) (English) and [README.zh-CN.md](README.zh-CN.md) (Chinese).

## Project Structure

- `README.md` / `README.zh-CN.md` - Main content with 16 tool categories
- `CONTRIBUTING.md` - Detailed contribution rules
- No build system, tests, or dependencies

## Entry Format

**Required pattern** (see [README.md](README.md#ai-code-assistants--editors) for examples):

```markdown
- [Tool Name](https://url) - Brief description ending with period.
```

**Description rules:**
- One sentence, factual, no marketing language ("best", "amazing")
- Start with capital, end with period
- Example: `[Cursor](https://cursor.sh/) - AI-first code editor built on VSCode with native chat and editing capabilities.`

## Categories & Placement

Tools should go in ONE primary category based on main function:
- **AI Code Assistants & Editors** - Full IDEs (GitHub Copilot, Cursor, Windsurf)
- **Code Completion Tools** - Real-time suggestions (Codeium, Tabnine)
- **Coding Agents** - Autonomous developers (Devin, Aider, OpenDevin)
- See [README.md](README.md#contents) for all 16 categories

**Avoid duplicates:** Search existing entries before adding. Each tool appears once.

## Multi-File Editing

When editing entries, **always update BOTH files simultaneously**:
- [README.md](README.md) - English version
- [README.zh-CN.md](README.zh-CN.md) - Chinese translation

Use `multi_replace_string_in_file` for efficiency when changing multiple entries.

## Link Updates

When updating URLs:
- Verify new URL is canonical/official (e.g., `https://openai.com/index/openai-codex/`)
- Update in both README files
- Check if description needs adjustment

## Common Patterns

**Moving entries between categories:**
1. Remove from original category in both files
2. Add to target category in both files
3. Ensure description fits new category context

**Removing duplicates:**
- Keep entry in most relevant category
- If tool serves multiple purposes, choose its PRIMARY function
- Reference [CONTRIBUTING.md](CONTRIBUTING.md#where-to-add-your-entry) for category guidance
