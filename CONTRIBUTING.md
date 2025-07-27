# Contributing to AAA Framework

Thank you for your interest in contributing to the **AI Aided Architecture (AAA) Framework**! This document provides guidelines and information for contributors.

## 🤝 How to Contribute

We welcome contributions from the community! Whether you're fixing a typo, adding new features, or improving documentation, your help makes the AAA Framework better for everyone.

### Types of Contributions

- **🐛 Bug Reports**: Help us identify and fix issues
- **✨ Feature Requests**: Suggest new capabilities or improvements
- **📚 Documentation**: Improve guides, examples, and API documentation
- **🔧 Code Improvements**: Enhance existing code or add new functionality
- **🎨 Templates**: Create better templates for common architectural scenarios
- **💡 Best Practices**: Share your experiences and lessons learned
- **🤖 AI Collaboration**: Improve AI prompts and collaboration methodologies

## 🚀 Getting Started

### Prerequisites

- Git installed on your machine
- A GitHub account
- Basic knowledge of Markdown (for documentation contributions)
- Familiarity with cloud architecture concepts (for technical contributions)

### Setting Up Your Development Environment

1. **Fork the repository**
   ```bash
   # Navigate to https://github.com/neverarchitectalone/framework
   # Click "Fork" in the top right corner
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/framework.git
   cd framework
   ```

3. **Add the original repository as upstream**
   ```bash
   git remote add upstream https://github.com/neverarchitectalone/framework.git
   ```

4. **Keep your fork updated** (recommended before starting work)
   ```bash
   git fetch upstream
   git checkout main
   git merge upstream/main
   git push origin main
   ```

## 📋 Contribution Guidelines

### Code of Conduct

By participating in this project, you agree to abide by our Code of Conduct. Please be respectful and inclusive in all interactions.

### Commit Message Guidelines

We follow conventional commit message format:

```
type(scope): description

[optional body]

[optional footer]
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

**Examples:**
```
feat(templates): add AWS serverless template
fix(docs): correct typo in architecture guide
docs(contributing): update contribution guidelines
```

### Branch Naming Convention

Use descriptive branch names:
- `feature/your-feature-name`
- `bugfix/issue-description`
- `docs/update-guide-name`
- `template/add-new-template`

## 🔄 Contribution Process

### 1. Create an Issue (Recommended)

Before making significant changes, please create an issue to discuss your proposed contribution. This helps ensure your work aligns with project goals.

### 1.5. Update Your Fork (Recommended)

Before starting work, ensure your fork is up to date:

```bash
git fetch upstream
git checkout main
git merge upstream/main
git push origin main
```

### 2. Create a Feature Branch

```bash
git checkout -b feature/your-feature-name
```

### 3. Make Your Changes

Follow these guidelines:

- **Documentation**: Use clear, concise language and include examples
- **Code**: Follow existing code style and patterns
- **Templates**: Ensure they follow AAA methodology principles
- **AI Sessions**: Document any AI collaboration sessions in `docs/ai-sessions/`

### 4. Test Your Changes

- For documentation: Review for clarity and accuracy
- For templates: Test the template in a sample project
- For code: Ensure it works as expected

### 5. Commit Your Changes

```bash
git add .
git commit -m "type(scope): description"
```

### 6. Push to Your Fork

```bash
git push origin feature/your-feature-name
```

### 7. Create a Pull Request

1. Go to your fork on GitHub
2. Click "Compare & pull request"
3. Fill out the PR template
4. Submit the PR

## 📝 Pull Request Guidelines

### PR Template

When creating a pull request, please include:

- **Description**: What does this PR do?
- **Type of Change**: Bug fix, feature, documentation, etc.
- **Testing**: How did you test your changes?
- **AI Collaboration**: If applicable, describe any AI collaboration sessions
- **Breaking Changes**: Are there any breaking changes?
- **Related Issues**: Link to any related issues

### Review Process

1. **Automated Checks**: Ensure all automated checks pass
2. **Code Review**: At least one maintainer will review your PR
3. **Feedback**: Address any feedback or requested changes
4. **Merge**: Once approved, your PR will be merged

## 🏗️ Project Structure

Understanding the project structure helps you contribute effectively:

```
framework/
├── docs/                    # Documentation
│   ├── ai-sessions/        # AI collaboration session logs
│   ├── templates/          # Template documentation
│   └── guides/             # User guides and tutorials
├── templates/              # Framework templates
├── examples/               # Example implementations
├── scripts/                # Utility scripts
└── CONTRIBUTING.md         # This file
```

## 🤖 AI Collaboration Guidelines

Since AAA Framework emphasizes AI collaboration, when contributing:

### Documenting AI Sessions

If you use AI tools during development, document the session:

```markdown
# AI Session: [Session Title]
Date: YYYY-MM-DD
AI Tool: [Tool Name]
Purpose: [What you were trying to accomplish]

## Session Summary
[Brief summary of the session]

## Key Insights
- [Insight 1]
- [Insight 2]

## Generated Content
[Any code, documentation, or ideas generated]

## Human Verification
[How you verified the AI's suggestions]
```

### AI Safety Reminder

Remember the core principle: **Never implement AI recommendations without human verification**. Always:
- Fact-check against official documentation
- Validate technical specifications
- Test generated code
- Review with experienced team members

## 🐛 Reporting Bugs

When reporting bugs, please include:

- **Description**: Clear description of the issue
- **Steps to Reproduce**: Detailed steps to reproduce the bug
- **Expected Behavior**: What you expected to happen
- **Actual Behavior**: What actually happened
- **Environment**: OS, browser, version information
- **Screenshots**: If applicable

## 💡 Suggesting Features

When suggesting features:

- **Problem**: What problem does this solve?
- **Solution**: How would you solve it?
- **Alternatives**: What alternatives have you considered?
- **Impact**: How would this benefit the community?

## 📞 Getting Help

If you need help contributing:

- **GitHub Issues**: Create an issue for questions
- **GitHub Discussions**: Join community discussions
- **Documentation**: Check existing documentation first
- **Community**: Reach out to the community

## 🎉 Recognition

Contributors will be recognized in:
- Project README (for significant contributions)
- Release notes
- Community acknowledgments

## 📄 License

By contributing to AAA Framework, you agree that your contributions will be licensed under the MIT License.

---

Thank you for contributing to the AAA Framework! Your help makes better architecture accessible to everyone. 🚀 