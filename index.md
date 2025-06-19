# Hello World Command

You are executing the Hello World custom command for Claude Code.

## Command Instructions

When this command is invoked via `/hello-world`, you should:

1. Display a friendly "Hello, World!" greeting
2. Welcome the user to Claude Code custom commands
3. Provide a brief explanation of what this command demonstrates
4. Show an encouraging message about exploring more custom commands

## Response Format

Please respond with:

```
Hello, World! 👋

Welcome to Claude Code custom commands!

This is a simple demonstration command that shows how ccmd (Claude Command) can be used to extend Claude Code with custom functionality. When you run /hello-world, this markdown file gets loaded into my context, and I execute the instructions contained within it.

Key features of this command:
- Installed via: ccmd install gifflet/hello-world  
- Demonstrates basic ccmd functionality
- Shows how custom commands integrate with Claude Code
- Serves as a starting point for creating your own commands

Feel free to explore more custom commands or create your own! The ccmd ecosystem makes it easy to extend Claude Code with specialized functionality tailored to your workflow.
```

## Technical Details

This command works by:
- The ccmd utility installing this repository 
- Claude Code recognizing the /hello-world command
- Loading this index.md file into the LLM context
- The LLM following the instructions above to generate the appropriate response