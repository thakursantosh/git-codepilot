# git-codepilot

## Overview

git-codepilot is an **agentic AI application** designed to act as an intelligent code pilot. It assists developers by providing code suggestions, explanations, and automating repetitive tasks directly within their development workflow.

## Features
- Context-aware code completions
- Natural language explanations of code snippets
- Automated refactoring and linting suggestions
- Seamless integration with popular editors and IDEs

## Installation

### Prerequisites
- Python 3.9 or newer
- `git` installed and available in your PATH

### Install via pip
```bash
pip install git-codepilot
```

### From source
```bash
# Clone the repository
git clone https://github.com/your-org/git-codepilot.git
cd git-codepilot

# Install dependencies
pip install -r requirements.txt

# Install the package in editable mode
pip install -e .
```

## Usage

After installation, you can invoke git-codepilot from the command line:
```bash
codepilot --help
```

Typical workflow:
1. **Start the assistant**: `codepilot start`
2. **Ask a question**: Type your query in natural language, e.g., `Explain this function`.
3. **Apply suggestions**: Accept or reject suggestions using the provided prompts.

For detailed usage instructions, refer to the [Documentation](docs/USAGE.md).

## Contributing

We welcome contributions! To get started:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Write tests for your changes and ensure all existing tests pass:
   ```bash
   pytest
   ```
4. Follow the coding style guidelines (PEP 8) and run the linter:
   ```bash
   flake8 .
   ```
5. Commit your changes with clear commit messages.
6. Push your branch and open a Pull Request against the `main` branch.

Please make sure your PR description includes:
- A brief description of the change.
- Reference to any related issue (e.g., `closes #12`).
- Any additional context needed for reviewers.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
