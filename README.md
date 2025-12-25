# Crush Commands

A collection of reusable command templates for [Crush](https://github.com/charmbracelet/crush), Charm's AI-powered CLI assistant.

## Overview

These commands provide structured prompts for common software development workflows, enforcing best practices like TDD, SOLID principles, and risk-based planning.

## Commands

### Code Generation

| Command | Description |
|---------|-------------|
| `code/go.md` | TDD-driven Go development with comprehensive design principles |
| `code/go-refactor.md` | Condensed Go refactoring guide |

### Project Initialization

| Command | Description |
|---------|-------------|
| `init/go.md` | Initialize a new Go project with git, README, and .gitignore |
| `init/python.md` | Initialize a Python project with virtual environment setup |

### Design & Planning

| Command | Description |
|---------|-------------|
| `requirement-to-design.md` | Convert requirements to detailed design using risk-based analysis |
| `design-to-tasks.md` | Transform design documents into prioritized todo items |
| `crit.md` | Critical review template with SOLID principles focus |

### Documentation

| Command | Description |
|---------|-------------|
| `docs/zet.md` | Generate zettelkasten notes from blog posts/articles |

### Testing

| Command | Description |
|---------|-------------|
| `tests/qa.md` | Generate comprehensive system test cases |

### Git

| Command | Description |
|---------|-------------|
| `commit.md` | Smart commit workflow with logical grouping |

## Usage

Place these files in `~/.config/crush/commands/` and invoke them with Crush:

## License

Apache License 2.0 - See [LICENSE](LICENSE) for details.
