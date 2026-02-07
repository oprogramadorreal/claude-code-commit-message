# Commit Message Suggester

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skill that analyzes your local git changes and suggests [conventional commit](https://www.conventionalcommits.org/) messages — without committing anything.

## Features

- Analyzes staged, unstaged, and untracked changes
- Generates messages following the Conventional Commits spec
- Matches the commit style already used in your repository
- Suggests splitting into multiple commits when changes span different concerns
- Read-only — never stages, commits, or modifies files

## Installation

Clone this repository into your Claude Code skills directory:

**macOS/Linux:**
```bash
git clone https://github.com/oprogramadorreal/commit-message ~/.claude/skills/claude-code-commit-message
```

**Windows:**
```bash
git clone https://github.com/oprogramadorreal/commit-message %USERPROFILE%\.claude\skills\claude-code-commit-message
```

## Usage

In Claude Code, use any of these:

- `/commit-message`
- "suggest a commit message"
- "generate commit message"
- "summarize my changes"

The skill will analyze your local changes and output a suggested commit message in a copyable code block.

## Requirements

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code)
- Git

## License

[MIT](LICENSE)
