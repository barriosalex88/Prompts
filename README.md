# Prompts

A personal collection of AI prompts, organized by category.

## Structure

```
prompts/
  coding/         Prompts for writing, reviewing, debugging, refactoring code
  writing/        Prompts for drafting, editing, and improving written content
  brainstorming/  Prompts for idea generation and exploration
  research/       Prompts for research, summarization, and analysis
  agents/         System prompts / instructions for agents and assistants
  productivity/   Prompts for planning, task management, and workflows
templates/
  prompt-template.md   Starting point for adding a new prompt
```

## Adding a new prompt

1. Copy `templates/prompt-template.md` into the relevant `prompts/<category>/` folder.
2. Rename it to a short, descriptive, kebab-case filename (e.g. `code-review-checklist.md`).
3. Fill in the template fields.
4. If none of the existing categories fit, create a new folder under `prompts/`.

## Format

Each prompt file follows this format:

```markdown
# Title

**Use case:** One-line description of when to use this prompt.

**Model:** (optional) any model-specific notes.

## Prompt

The actual prompt text goes here.

## Notes

Optional tips, variations, or example output.
```
