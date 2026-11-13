# FrameKit
 
en English | [🇷🇺 Русский](README.ru.md)
 
**Generate project structure for your tech stack.**
 
FrameKit is a VS Code extension that creates a ready-to-use project structure in a few clicks.
 
> ⚠️ **Work in progress.** The project is under active development and is not published to the Marketplace yet. Features listed below are planned unless marked as done.
 
## Idea
 
Starting a new project usually means creating the same folders and files again and again. FrameKit removes that routine:
 
1. Run the command **FrameKit: Create Project** from the Command Palette
2. Choose a technology or stack (Node/TypeScript, Python, Go, ...)
3. Choose the target folder
4. Get the project structure generated for you
## Features
 
- [ ] Command "FrameKit: Create Project"
- [ ] Technology selection via Quick Pick
- [ ] Built-in templates: Node/TypeScript, Python, Go
- [ ] Templates stored as plain folders and JSON/YAML descriptions (easy to extend without writing TypeScript)
- [ ] Custom user templates
- [ ] Template variables (project name, author, etc.)
## Roadmap
 
- **v0.1** — working prototype: one command, three templates
- **v0.2** — more stacks (FastAPI, Django, Go `cmd/` + `internal/`, React, etc.)
- **v0.3** — custom templates
- **Later** — core logic extracted into a separate package, CLI and support for other editors
## Installation
 
Not available yet. Once published, the extension will be installable from the VS Code Marketplace by searching for **FrameKit**.
 
## Development
 
Requirements: [Node.js](https://nodejs.org/) (LTS) and [VS Code](https://code.visualstudio.com/).
 
```bash
git clone https://github.com/your-username/framekit.git
cd framekit
npm install
```
 
Open the folder in VS Code and press **F5**. A new window (Extension Development Host) will open with the extension loaded. Run commands from the Command Palette (`Ctrl+Shift+P`).
 
## Contributing
 
Contributions are welcome, especially new project templates for different technologies. You do not need to know TypeScript to add a template: templates are plain files and descriptions.
 
- Found a bug or have an idea? [Open an issue](../../issues)
- Want to add a template? Look for issues labeled `templates` or `good first issue`
## License
 
[MIT](LICENSE)
