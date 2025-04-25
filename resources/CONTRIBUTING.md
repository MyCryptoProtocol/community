# Contributing to MyCryptoProtocol

Thank you for your interest in contributing to MyCryptoProtocol (MCP)! This document provides guidelines and instructions for contributing to the project.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Workflow](#development-workflow)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Commit Message Guidelines](#commit-message-guidelines)
- [Community Contributions](#community-contributions)

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Bug reports are valuable contributions. Before creating a bug report, please check the issue tracker to avoid duplicates. When creating a bug report, include:

- A clear, descriptive title
- Steps to reproduce the issue
- Expected and actual behavior
- Screenshots (if applicable)
- Environment details (OS, browser, etc.)

### Suggesting Enhancements

Enhancement suggestions help improve MCP. When suggesting an enhancement:

- Use a clear, descriptive title
- Provide a detailed description of the suggested enhancement
- Explain why it would be useful
- Include mockups or examples if possible

### Code Contributions

Code contributions are welcome in the following areas:

- **Core Protocol**: Improvements to the Solana programs in [mcp-core](https://github.com/MyCryptoProtocol/mcp-core)
- **Agents**: New or improved agent templates in [mcp-agents](https://github.com/MyCryptoProtocol/mcp-agents)
- **Server**: Enhancements to the reference server in [mcp-server](https://github.com/MyCryptoProtocol/mcp-server)
- **Examples**: New examples showcasing MCP usage in [mcp-examples](https://github.com/MyCryptoProtocol/mcp-examples)
- **Documentation**: Improvements to docs in [mcp-docs](https://github.com/MyCryptoProtocol/mcp-docs)
- **Community Resources**: Resources that help community members engage with the project

### MCP Server Implementations

A valuable way to contribute is by creating new MCP server implementations that connect AI agents to various crypto services. See the [MCP Server Implementation Guide](../resources/SERVER_IMPLEMENTATION_GUIDE.md) for details.

## Development Workflow

1. **Fork the repository** you wish to contribute to
2. **Create a branch** for your work (`git checkout -b feature/your-feature-name`)
3. **Make your changes** following the coding standards
4. **Run tests** to ensure your changes don't break existing functionality
5. **Commit your changes** using the [commit message guidelines](#commit-message-guidelines)
6. **Push your branch** to your fork
7. **Submit a pull request** to the main repository

### Setting Up Your Development Environment

```bash
# Clone your fork
git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
cd REPOSITORY-NAME

# Add the original repository as upstream
git remote add upstream https://github.com/MyCryptoProtocol/REPOSITORY-NAME.git

# Install dependencies
npm install

# For mcp-core (Solana programs)
cd mcp-core
anchor build
```

## Pull Request Guidelines

- PRs should focus on a single feature or fix
- Link related issues in the PR description
- Include tests for new functionality
- Update documentation as needed
- Ensure all tests pass before submitting
- Be responsive to feedback and review comments

## Commit Message Guidelines

We follow a structured commit message format to maintain a clear project history:

```
type(scope): short description

Longer description if needed
```

Types include:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Formatting changes
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

Example: `feat(agents): Add support for NFT market analysis`

## Community Contributions

Beyond code, there are many ways to contribute:

- **Documentation**: Improving guides, examples, and explanations
- **Translations**: Translating documentation to other languages
- **Community Support**: Helping others in Discord, forums, or GitHub discussions
- **Content Creation**: Writing blog posts, creating videos, or other content
- **Educational Resources**: Creating tutorials or learning resources
- **Governance Participation**: Voting on improvement proposals

---

Thank you for contributing to MyCryptoProtocol! Your efforts help build a more accessible and powerful bridge between AI and crypto.
