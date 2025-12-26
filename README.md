# Crush Commands

A collection of reusable command templates for [Crush](https://github.com/charmbracelet/crush), Charm's AI-powered CLI assistant.

## Overview

These commands provide structured prompts for common software development workflows, enforcing best practices like TDD, SOLID principles, and risk-based planning.

## Commands

### Code Generation (`code/`)

| Command | Description |
|---------|-------------|
| `go.md` | TDD-driven Go development with comprehensive design principles |
| `go-refactor.md` | Condensed Go refactoring guide |

### Project Initialization (`init/`)

| Command | Description |
|---------|-------------|
| `go.md` | Initialize a new Go project with git, README, and .gitignore |
| `python.md` | Initialize a Python project with virtual environment setup |

### Design & Planning (`design/`)

| Command | Description |
|---------|-------------|
| `karya.md` | Full-stack software engineering workflow using note/todo/zet MCPs |
| `requirement-to-design.md` | Convert requirements to detailed design using risk-based analysis |
| `design-to-tasks.md` | Transform design documents into prioritized todo items |

### Documentation (`docs/`)

| Command | Description |
|---------|-------------|
| `zet.md` | Generate zettelkasten notes from blog posts/articles |
| `zet-fullsite.md` | Generate hierarchical zettelkasten from entire documentation sites |

### Testing (`tests/`)

| Command | Description |
|---------|-------------|
| `qa.md` | Generate comprehensive system test cases |

### Other

| Command | Description |
|---------|-------------|
| `crit.md` | Critical review template with SOLID principles focus |
| `commit.md` | Smart commit workflow with logical grouping |

## Usage

Place these files in `~/.config/crush/commands/` and invoke them with Crush:

```bash
crush /code/go
crush /init/python
crush /design/karya
```

## License

Apache License 2.0 - See [LICENSE](LICENSE) for details.
