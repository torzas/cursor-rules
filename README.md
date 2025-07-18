# Cursor Rules

A framework for codifying and enforcing project-specific rules, best practices, and development standards. `cursor-rules` helps teams and AI assistants maintain code quality, consistency, and workflow discipline across software projects.

## Features
- 📋 **Rule Definitions**: Write and organize rules for code quality, project structure, commit messages, documentation, and more.
- 🛡️ **Best Practices**: Enforce backend, Go, and general software engineering best practices.
- 🏗️ **Project Structure Guidance**: Recommend and validate folder and file layouts.
- 🤖 **AI Assistant Integration**: Designed for use with AI pair programming tools and code review bots.
- 🧩 **Extensible**: Add your own rules for any language, framework, or workflow.

## Getting Started
1. **Clone or copy** this repository (or directory) into your project:
   ```bash
   git clone https://github.com/torzas/cursor-rules.git
   # or copy the folder into your repo
   cp -r cursor-rules/ <your-project>/cursor-rules/
   ```
2. **Reference rules** in your development workflow, code reviews, or with AI assistants.
3. **Customize**: Add or edit rule files to fit your project's needs.

## Folder Structure
```
cursor-rules/
  base/           # General rules (clean code, code quality, commits, docs, gitflow)
  go/             # Go-specific backend and database rules
  htmx-go/        # Rules for HTMX, Go, and Fiber projects
  README.md       # This file
```

## Example Usage
- In a pull request:  
  _"This change follows the `base/clean-code` and `go/backend-general-expert` rules for maintainability and security."_
- In an AI assistant prompt:  
  _"Apply the `htmx-go/recommended-folder-structure` rule to reorganize the project."_

## Contributing
- Add new rules as Markdown or text files in the appropriate subdirectory.
- Use clear, actionable language and provide examples where possible.
- Update this README if you add major new rule categories.

## License
MIT License. See [LICENSE](LICENSE) for details.

