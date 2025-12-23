# Neo Tools Extension

This extension provides tools powered by the Bun runtime.

## Prompts Available

### `git_commit`
Use this prompt when the user asks to "smart commit", "write a commit message", or "generate a commit".
It will:
1. Automatically run `git add .`
2. Get the staged diff.
3. Generate a high-quality Conventional Commit message using a strict senior architect persona.