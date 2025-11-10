# Contributing to Offline Labs

Thank you for your interest in contributing to Offline Labs! We're excited to have you join our community of developers, designers, and enthusiasts working together to build free, open source, and ad-free alternatives for everyday apps.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
- [Development Guidelines](#development-guidelines)
- [Coding Standards](#coding-standards)
- [Commit Guidelines](#commit-guidelines)
- [Pull Request Process](#pull-request-process)
- [Community](#community)

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please read it before contributing.

## How Can I Contribute?

There are many ways to contribute to Offline Labs:

### 🐛 Reporting Bugs

- Check if the bug has already been reported in the issues
- Use a clear and descriptive title
- Describe the exact steps to reproduce the problem
- Provide specific examples and explain the expected vs. actual behavior
- Include screenshots if relevant
- Note your environment (OS, browser version, etc.)

### 💡 Suggesting Enhancements

- Check if the enhancement has already been suggested
- Use a clear and descriptive title
- Provide a detailed description of the suggested enhancement
- Explain why this enhancement would be useful
- List any similar features in other applications if applicable

### 📝 Documentation

- Fix typos or clarify existing documentation
- Add missing documentation
- Translate documentation
- Create tutorials or examples

### 💻 Code Contributions

- Pick an issue labeled `good first issue` if you're new
- Look for issues labeled `help wanted`
- Propose new features or improvements
- Fix bugs

### 🎨 Design Contributions

- Improve UI/UX
- Create mockups for new features
- Design icons or graphics
- Improve accessibility

## Getting Started

1. **Fork the repository** you want to contribute to
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/PROJECT_NAME.git
   cd PROJECT_NAME
   ```
3. **Create a branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
   or
   ```bash
   git checkout -b fix/your-bug-fix
   ```
4. **Make your changes** following our development guidelines
5. **Test your changes** thoroughly
6. **Commit your changes** with clear, descriptive messages
7. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
8. **Open a Pull Request** to the main repository

## Development Guidelines

### Our Core Principles

All contributions should align with our core principles:

#### 🔌 Offline First
- Design features to work without an internet connection
- Handle offline/online transitions gracefully
- Cache data appropriately
- Provide clear feedback about connection status

#### 🔒 Privacy by Design
- Don't collect unnecessary data
- Store sensitive data securely
- Provide clear privacy controls
- Default to the most private option
- Be transparent about data usage

#### 🌐 Open Source
- Write readable, maintainable code
- Document your work thoroughly
- Use open source dependencies when possible
- Avoid proprietary or restrictive licenses

### General Guidelines

- **Follow coding style guidelines**: Maintain consistency with existing code
- **Write clear, documented code**: Use comments where necessary, write self-documenting code
- **Test your changes thoroughly**: Include unit tests, integration tests, and manual testing
- **Keep commits focused and atomic**: One logical change per commit
- **Be respectful and inclusive**: Follow our Code of Conduct
- **Help others learn and grow**: Review PRs constructively, answer questions patiently
- **Share knowledge and experience**: Contribute to documentation and discussions

## Coding Standards

### Code Quality

- Write clean, readable code
- Follow the existing code style in the project
- Use meaningful variable and function names
- Keep functions small and focused
- Avoid code duplication (DRY principle)
- Comment complex logic

### Documentation

- Add docstrings/JSDoc comments to functions and classes
- Update README if you change functionality
- Document any new dependencies or setup steps
- Include inline comments for complex algorithms

### Testing

- Write tests for new features
- Ensure existing tests pass
- Aim for good test coverage
- Test edge cases and error conditions
- Test offline functionality where applicable

### Performance

- Consider performance implications of your changes
- Avoid unnecessary computations
- Optimize for offline usage (minimize storage, optimize caching)
- Profile code if making performance-critical changes

### Security

- Never commit secrets or API keys
- Sanitize user input
- Follow security best practices for the language/framework
- Report security issues privately

## Commit Guidelines

### Commit Messages

Write clear, descriptive commit messages:

```
type: Brief summary (50 characters or less)

More detailed explanation if necessary. Wrap at 72 characters.
Explain what and why, not how.

- Bullet points are okay
- Use present tense: "Add feature" not "Added feature"
- Reference issues: "Fixes #123" or "Relates to #456"
```

### Commit Types

- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, missing semicolons, etc.)
- `refactor`: Code refactoring without changing functionality
- `test`: Adding or updating tests
- `chore`: Maintenance tasks, dependency updates

### Examples

```
feat: Add offline mode indicator to status bar

Implements a visual indicator that shows connection status.
Users can now see at a glance whether they're online or offline.

Fixes #42
```

```
fix: Prevent data loss when going offline during sync

Added proper error handling and retry logic for sync operations.
Data is now queued and retried when connection is restored.

Relates to #78
```

## Pull Request Process

1. **Ensure your code follows our guidelines**
   - Code is well-documented
   - Tests are passing
   - Style guidelines are followed

2. **Update documentation**
   - README if functionality changes
   - Inline code comments
   - Any relevant wiki or docs

3. **Write a clear PR description**
   - What does this PR do?
   - Why is this change needed?
   - How has it been tested?
   - Screenshots for UI changes

4. **Link related issues**
   - Use "Fixes #123" or "Closes #123" for issues this PR resolves
   - Use "Relates to #456" for related issues

5. **Be responsive**
   - Address review comments promptly
   - Ask questions if feedback is unclear
   - Be open to suggestions

6. **Keep it focused**
   - One feature or fix per PR
   - Avoid mixing unrelated changes
   - Keep PRs reasonably sized

### PR Checklist

Before submitting, ensure:

- [ ] Code follows the project's style guidelines
- [ ] Self-review of code completed
- [ ] Code is well-commented, especially complex parts
- [ ] Documentation has been updated
- [ ] Changes generate no new warnings
- [ ] Tests have been added/updated and pass
- [ ] Offline functionality works as expected (if applicable)
- [ ] Privacy implications have been considered
- [ ] Dependent changes have been merged

## Community

### Getting Help

- **Discussions**: Ask questions in GitHub Discussions
- **Issues**: Report bugs or request features
- **Documentation**: Check project docs and README files

### Reviewing Pull Requests

We welcome your reviews on others' PRs:

- Be constructive and respectful
- Ask questions to understand the change
- Suggest improvements clearly
- Acknowledge good work
- Help others learn

### Staying Connected

- Watch the repository for updates
- Participate in discussions
- Help answer questions from other contributors
- Share your experience and learnings

## Recognition

We value all contributions! Contributors will be:

- Listed in project documentation
- Mentioned in release notes for significant contributions
- Appreciated and recognized by the community

## Questions?

Don't hesitate to ask! We're here to help:

- Open an issue with your question
- Start a discussion
- Reach out to maintainers

Thank you for contributing to Offline Labs! Together, we're building a better, more private, and open future for everyone. 🚀
