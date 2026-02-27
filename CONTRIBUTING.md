# Contributing to PM Prompt Library

Thanks for your interest in contributing! This library gets better with every prompt submitted by the community.

## How to Submit a Prompt

1. **Fork this repo** and create a branch from `main`.
2. **Create a new file** in the appropriate category folder under `prompts/`. If no category fits, propose a new one.
3. **Follow the prompt format** (see `prompts/TEMPLATE.md` if available, or use an existing prompt as reference):
   - **Title**: A clear, descriptive name
   - **Use case**: When a PM would use this prompt
   - **The prompt**: The actual text, with `[PLACEHOLDER]` markers for inputs
   - **Example output**: A brief sample of what good output looks like
   - **Tips**: Any advice for getting better results
4. **Test your prompt** with Claude or another LLM before submitting. Make sure it produces useful output.
5. **Open a pull request** with a short description of what the prompt does and why it's useful.

## Quality Guidelines

- Prompts should solve a real PM workflow problem, not be generic.
- Use clear placeholder syntax: `[COMPANY NAME]`, `[METRIC]`, `[USER SEGMENT]`.
- Keep prompts focused. One prompt = one task. Don't combine "write a PRD and also do competitive analysis."
- Include context-setting instructions in the prompt itself (role, audience, constraints).

## What Makes a Great Prompt

- **Specific**: "Analyze churn for a B2B SaaS product" beats "analyze churn."
- **Structured**: Tells the LLM what format to use for output.
- **Testable**: You can look at the output and clearly judge if it's good or not.
- **Reusable**: Works across different companies/products with minimal edits.

## Reporting Issues

If a prompt produces poor results or has errors, open an issue with:
- The prompt you used
- The output you got
- What you expected instead

## Code of Conduct

Be respectful. We're all here to build better PM tools.
