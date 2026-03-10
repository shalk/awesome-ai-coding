# Project Guidelines

Awesome AI Coding is a curated list following the [Awesome List](https://awesome.re) format. This is a documentation-only repository with two synchronized files: [README.md](README.md) (English) and [README.zh-CN.md](README.zh-CN.md) (Chinese).

## Project Structure

- `README.md` / `README.zh-CN.md` - Main content with 16 tool categories
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
- **Coding Agents** - Autonomous developers (Devin, Aider, OpenDevin)

**Avoid duplicates:** Search existing entries before adding. Each tool appears once.

## Primary Function Rule

Each tool goes in ONE category based on its PRIMARY function:

**Decision process:**
1. Identify the tool's main use case (what users primarily use it for)
2. Place it in the corresponding functional category
3. If unclear, ask: "If this tool had only ONE feature, which would it be?"

**Category boundaries:**
- **"AI Code Assistants & Editors"**: Full environments or major IDE extensions (Continue, Cursor, GitHub Copilot)
- **"Code Completion Tools"**: Tools focused ONLY on autocomplete/suggestions (Codeium, Tabnine)
- **"Coding Agents"**: Autonomous tools that write/edit code independently (Aider, Devin, OpenDevin, Plandex)
- **"Code Review & Quality"**: Review and refactoring (NOT security-focused)
- **"Security & Vulnerability Detection"**: Vulnerability detection, secrets scanning, security fixes
- **"Editor Integrations"**: Lightweight plugins (NOT full-featured assistants like Continue)

**Examples:**
- Continue: Primary function is AI-assisted coding → "AI Code Assistants & Editors"
- Pixee: Primary function is security fixes → "Security & Vulnerability Detection"
- Pythagora: Primary function is app building → "App Builders & Generators"
- Plandex: Primary function is autonomous coding → "Coding Agents"

**Deprecated patterns:**
- ❌ Don't create "Natural Language to X" categories (redundant with agents/builders)
- ❌ Don't duplicate tools across categories
- ❌ Don't organize by AI provider or interface type in main structure (use metadata section)

## Duplicate Prevention

**Before adding a tool:**
1. Search both README files for the tool name (exact and similar names)
2. Use Grep to check: `grep -i "tool-name" README.md README.zh-CN.md`
3. If found, verify it's not a duplicate or naming collision

**If tool appears in multiple categories:**
- It's likely a duplicate - keep only in PRIMARY function category
- Update description to clarify primary function if needed

**Common duplicate scenarios:**
- Tool listed in both "AI Code Assistants" and "Editor Integrations" → Keep in "AI Code Assistants"
- Tool listed in both "Code Review" and "Security" → Determine primary function (quality vs. security)
- Tool listed in both "Coding Agents" and "App Builders" → Determine primary function (general coding vs. app generation)

## Handling Multi-Purpose Tools

**Tools that serve multiple functions:**
- Choose the PRIMARY use case (what users mainly use it for)
- Mention secondary capabilities in the description
- Example: "Continue - Open-source autopilot for VS Code and JetBrains with code completion and chat." (Primary: Assistant, Secondary: Completion)

**Platform-specific versions:**
- If it's the SAME tool on different platforms → ONE entry, mention all platforms
- Example: "Continue - Open-source autopilot for VS Code and JetBrains"

**Ecosystem expansion:**
- When tools add new model support, update description but DON'T move categories
- Category is based on function, not underlying AI model

## Multi-File Editing

When editing entries, **always update BOTH files simultaneously**:
- [README.md](README.md) - English version
- [README.zh-CN.md](README.zh-CN.md) - Chinese translation

Use `multi_replace_string_in_file` for efficiency when changing multiple entries.

## Common Patterns

**Moving entries between categories:**
1. Remove from original category in both files
2. Add to target category in both files
3. Ensure description fits new category context

**Removing duplicates:**
- Keep entry in most relevant category
- If tool serves multiple purposes, choose its PRIMARY function
