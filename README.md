# Frontend Framework Selector

A VS Code extension that serves as a decision-support tool for developers choosing frontend frameworks. Rather than providing a single recommendation, it analyzes user requirements and project context to present a comprehensive comparison of React, Vue, Angular, and Svelte with clear explanations of trade-offs, strengths, and weaknesses.

## Features

- Interactive framework comparison through VS Code command palette
- Context-aware analysis based on current project structure
- Weighted scoring system with transparent explanations
- Comprehensive comparison results in WebView interface
- Support for React, Vue, Angular, and Svelte frameworks

## Development

### Prerequisites

- Node.js (version 16 or higher)
- VS Code

### Setup

1. Clone the repository
2. Run `npm install` to install dependencies
3. Press `F5` to open a new Extension Development Host window
4. Run the command `Frontend Framework Selector: Compare Frameworks` from the command palette

### Building

- `npm run compile` - Compile TypeScript to JavaScript
- `npm run watch` - Watch for changes and compile automatically
- `npm run lint` - Run ESLint

## Usage

1. Open VS Code in your project directory
2. Open the command palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
3. Search for "Frontend Framework Selector: Compare Frameworks"
4. Follow the interactive prompts to specify your requirements
5. View the comprehensive comparison results in the WebView panel

## License

MIT