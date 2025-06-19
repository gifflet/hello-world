# hello-world

A simple Hello World custom command for Claude Code, installable via ccmd.

## What it does

This command demonstrates the basic functionality of Claude Code custom commands. When executed via `/hello-world` in Claude Code, it loads the `index.md` file into the LLM context and executes the instructions contained within it, displaying a friendly greeting and explanation of how custom commands work.

## Installation

```bash
ccmd install gifflet/hello-world
```

## Usage

After installation, use in Claude Code:

```
/hello-world
```

The command will display a welcome message explaining how Claude Code custom commands work.

## How it works

1. The ccmd utility installs this repository
2. Claude Code recognizes the `/hello-world` command
3. When invoked, Claude Code loads `index.md` into the LLM context
4. The LLM follows the instructions in `index.md` to generate the appropriate response

## Development

This repository serves as:
- A basic example of Claude Code custom commands
- A test case for ccmd integration
- A starting point for developers creating their own custom commands
- A demonstration of how markdown files can contain LLM instructions