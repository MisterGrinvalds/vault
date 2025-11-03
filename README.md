# vault

A centralized repository for storing Obsidian vaults, AI configurations, and other important content.

## Repository Structure

```
vault/
├── Notes/              # Obsidian vaults and general notes
├── AI-Config/          # AI tool configurations and prompts
│   ├── claude/         # Claude AI specific files
│   │   ├── agents/     # Custom agent definitions
│   │   └── commands/   # Saved commands and workflows
│   └── prompts/        # Reusable prompt templates
├── Other/              # Miscellaneous content
└── README.md           # This file
```

## Purpose

This repository serves as a structured storage location for:

1. **Notes** - Obsidian vaults for personal knowledge management
2. **AI Configuration** - Claude commands, custom agents, and AI prompts
3. **Other** - Miscellaneous files, scripts, and reference materials

## Getting Started

### Working with Obsidian Vaults

1. Navigate to the `Notes/` directory
2. Create a new folder for your vault or use an existing one
3. Open the folder as an Obsidian vault
4. Start taking notes!

### Managing AI Configurations

Store your AI-related files in the `AI-Config/` directory:
- Custom agent definitions in `AI-Config/claude/agents/`
- Saved commands in `AI-Config/claude/commands/`
- Reusable prompts in `AI-Config/prompts/`

### Other Content

Use the `Other/` directory for any content that doesn't fit the above categories.

## Version Control Best Practices

- Each directory contains a README with more specific information
- Obsidian workspace files are excluded via `.gitignore`
- Commit regularly to track changes and maintain history
- Use descriptive commit messages

## License

MIT License - See [LICENSE](LICENSE) file for details