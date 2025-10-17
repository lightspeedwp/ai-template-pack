# AI Template Pack

Curated templates for ChatGPT, Claude, Gemini, GitHub Copilot & Copilot Spaces, plus model guides and repo-setup prompts. For agencies and product teams. Markdown-first with structured folders. MIT-licensed.

## 🎯 Purpose

This repository provides a standardized collection of AI templates and prompts designed for:
- **Agencies** building AI-powered solutions for clients
- **Product teams** integrating AI into their workflows
- **Developers** seeking consistent AI prompt patterns
- **Teams** wanting to share and maintain AI knowledge

## 📁 Structure

```
/chatgpt/           # ChatGPT-specific templates
/claude/            # Anthropic Claude templates
/gemini/            # Google Gemini templates
/copilot/           # GitHub Copilot templates
/copilot-spaces/    # GitHub Copilot Spaces templates
/figma-make/        # Figma + Make.com automation templates
/models/            # General model guides and comparisons
/github-new-repo/   # Repository setup and scaffolding prompts
/dist/              # Release ZIPs and packaged templates
```

Each model folder may contain category subfolders (e.g., `/sales/`, `/support/`, `/development/`).

## 🚀 Quick Start

### Using Templates

1. **Browse by AI Model**: Navigate to your preferred AI platform folder
2. **Find by Category**: Look for use case folders like `sales`, `support`, `development`
3. **Copy & Customize**: Use the template structure and customize for your needs
4. **Follow the Format**: Each template includes Goal, Inputs, Instructions, Quality checks, Safety limits, and Examples

### Contributing Templates

1. Fork this repository
2. Create templates following our [Template Spec](https://github.com/lightspeedwp/.github/blob/develop/docs/ai/template-spec.md)
3. Use kebab-case naming: `{category}-{purpose}.md`
4. Include required front matter and sections
5. Submit a pull request

## 📋 Template Format

Every template follows this standardized structure:

```markdown
---
title: Short descriptive title
model: chatgpt|claude|gemini|copilot
use_case: sales|support|development|research|general
status: draft|ready
version: 1.0.0
author: Team/Person
last_updated: YYYY-MM-DD
---

## Goal
Single sentence describing the outcome.

## Inputs
Variables users must provide before using the template.

## Instructions
Numbered steps for the AI to follow.

## Quality Checks
Acceptance criteria for evaluating results.

## Safety & Limits
What not to do; ethical and practical boundaries.

## Examples
At least one complete example showing expected input/output.
```

## 🔄 Release Process

### Automated Releases

Templates are packaged into ZIP files in the `/dist/` directory for easy distribution:

- **Latest Release**: `/dist/ai-templates-latest.zip`
- **Versioned Releases**: `/dist/ai-templates-v{version}.zip`
- **Model-Specific**: `/dist/{model}-templates-v{version}.zip`

### Extraction Instructions

```bash
# Download latest release
curl -L -o ai-templates.zip "https://github.com/lightspeedwp/ai-template-pack/raw/main/dist/ai-templates-latest.zip"

# Extract to your project
unzip ai-templates.zip -d ./ai-templates/

# Use in your workflow
cp ai-templates/chatgpt/sales/* ./prompts/
```

## 🤝 Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md).

### Types of Contributions

- **New Templates**: Add templates for new use cases or AI models
- **Template Improvements**: Enhance existing templates with better examples or instructions
- **Documentation**: Improve guides, examples, and explanations
- **Bug Reports**: Report issues with templates or documentation
- **Feature Requests**: Suggest new template categories or improvements

### Contribution Process

1. Check existing [issues](../../issues) and [pull requests](../../pulls)
2. Create an issue to discuss major changes
3. Follow the template spec when adding new templates
4. Test templates with the target AI model
5. Submit pull request with clear description

## 📚 Resources

- [Template Specification](https://github.com/lightspeedwp/.github/blob/develop/docs/ai/template-spec.md)
- [AI Model Guides](/models/)
- [Contributing Guidelines](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Release Notes](../../releases)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- [Issues](../../issues) - Report bugs or request features
- [Discussions](../../discussions) - Community conversations
- [Releases](../../releases) - Download packaged templates
- [LightSpeed WP](https://lightspeedwp.com) - Our agency

---

Built with ❤️ by [LightSpeed WP](https://lightspeedwp.com) for the AI community.
