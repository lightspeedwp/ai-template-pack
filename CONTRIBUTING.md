# Contributing to AI Template Pack

Thank you for your interest in contributing to the AI Template Pack! This repository is a community-driven collection of AI templates and prompts designed to help agencies, product teams, and developers work more effectively with AI.

## 🎯 How to Contribute

### Template Contributions

We welcome new templates that follow our [Template Specification](https://github.com/lightspeedwp/.github/blob/develop/docs/ai/template-spec.md). Here's how to contribute:

1. **Fork the repository** and create a new branch
2. **Choose the right folder** for your template:
   - `/chatgpt/` - ChatGPT-specific templates
   - `/claude/` - Anthropic Claude templates  
   - `/gemini/` - Google Gemini templates
   - `/copilot/` - GitHub Copilot templates
   - `/copilot-spaces/` - GitHub Copilot Spaces templates
   - `/figma-make/` - Figma + Make.com automation
   - `/models/` - General model guides
   - `/github-new-repo/` - Repository setup prompts

3. **Follow naming conventions**: Use kebab-case (`{category}-{purpose}.md`)
4. **Include required sections** and front matter
5. **Test your template** with the target AI model
6. **Submit a pull request** with a clear description

### Template Format Requirements

Every template must include:

```markdown
---
title: Short descriptive title
model: chatgpt|claude|gemini|copilot
use_case: sales|support|development|research|general
status: draft|ready
version: 1.0.0
author: Your Name/Team
last_updated: YYYY-MM-DD
---

## Goal
Single sentence describing the desired outcome.

## Inputs
Variables users must provide (e.g., company name, product details).

## Instructions
Numbered steps for the AI to follow.

## Quality Checks
Acceptance criteria for evaluating results.

## Safety & Limits
What not to do; ethical and practical boundaries.

## Examples
At least one complete example with sample input/output.
```

### Quality Standards

- **Tested**: Templates should be tested with their target AI model
- **Clear**: Instructions should be unambiguous and actionable
- **Safe**: Templates should include appropriate safety guidelines
- **Useful**: Templates should solve real-world problems
- **Complete**: All required sections must be included

## 🐛 Bug Reports

Found an issue with a template or the repository? Please help us improve by:

1. **Search existing issues** to avoid duplicates
2. **Use our issue templates** for consistent reporting
3. **Include specific details**:
   - Which template has the issue
   - What AI model you're using
   - Expected vs actual behavior
   - Steps to reproduce

## 💡 Feature Requests

Have ideas for new templates or improvements? We'd love to hear them!

1. **Check existing issues** for similar requests
2. **Use the feature request template**
3. **Describe the use case** and potential impact
4. **Consider contributing** the feature yourself

## 🔄 Development Process

### Branch Naming

- `feature/template-name` - New templates
- `fix/issue-description` - Bug fixes
- `docs/section-name` - Documentation updates
- `refactor/area-name` - Code/structure improvements

### Pull Request Process

1. **Create descriptive PR title**: `Add: ChatGPT sales email template`
2. **Fill out PR template** completely
3. **Link related issues**: `Closes #123`
4. **Request review** from maintainers
5. **Address feedback** promptly

### Review Criteria

Pull requests are reviewed for:

- **Template Quality**: Follows specification and quality standards
- **Usefulness**: Addresses real-world use cases
- **Safety**: Includes appropriate guardrails
- **Documentation**: Clear instructions and examples
- **Testing**: Evidence of testing with target AI model

## 📋 Issue Types

We use specific issue templates for different contribution types:

- **Bug Report**: Problems with existing templates
- **Feature Request**: New template ideas or improvements
- **Enhancement**: Improvements to existing templates
- **Documentation**: Updates to guides and documentation
- **Template Submission**: New template contributions

## 🤝 Community Guidelines

### Code of Conduct

This project follows our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold these standards of behavior.

### Communication

- **Be respectful** in all interactions
- **Be constructive** when providing feedback
- **Be patient** with new contributors
- **Be collaborative** in problem-solving

### Recognition

Contributors are recognized through:

- **Author attribution** in template front matter
- **Contributor list** in repository
- **Release notes** for significant contributions
- **Community mentions** in discussions

## 🚀 Getting Started

New to contributing? Here are some good first contributions:

1. **Fix typos** or improve documentation
2. **Add examples** to existing templates
3. **Test templates** and report issues
4. **Improve template formatting** or structure
5. **Create simple templates** for common use cases

## 📚 Resources

- [Template Specification](https://github.com/lightspeedwp/.github/blob/develop/docs/ai/template-spec.md)
- [GitHub Flow Guide](https://guides.github.com/introduction/flow/)
- [Writing Good Commit Messages](https://chris.beams.io/posts/git-commit/)
- [AI Safety Best Practices](https://www.anthropic.com/safety)

## 🆘 Getting Help

Need help contributing? Here are your options:

- **GitHub Issues**: Ask questions using the help template
- **GitHub Discussions**: Community conversations and Q&A
- **Documentation**: Check our guides and specifications
- **Examples**: Review existing templates for patterns

## 📄 License

By contributing to this repository, you agree that your contributions will be licensed under the MIT License.

---

Thank you for helping make AI more accessible and useful for everyone! 🙏