# Contributing to Offline Labs

Thank you for your interest in contributing to Offline Labs! We're excited to have you join our community of developers, designers, and enthusiasts working together to build free, open source, and ad-free alternatives for everyday apps.

## Table of Contents

- [Core Principles](#core-principles)
- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
- [Development Guidelines](#development-guidelines)
- [Coding Standards](#coding-standards)
- [Commit Guidelines](#commit-guidelines)
- [Pull Request Process](#pull-request-process)
- [Community](#community)

## Core Principles

**These principles are non-negotiable and form the foundation of everything we build at Offline Labs. All contributions must align with these values. Any malicious attempt to circumvent these principles will result in a complete ban from future collaborations.**

### 1. 🔌 Offline First

**Your apps should work when you need them most, even without internet connection.**

We do not restrict integrating Offline Labs projects with online tools. The key is to avoid unnecessary integrations that lock users out of features that are perfectly accessible offline. Examples include apps that require account creation when most of their functions don't need to be tied to anything in the cloud.

**Guidelines:**
- Design features to work without an internet connection
- Handle offline/online transitions gracefully
- Cache data appropriately
- Provide clear feedback about connection status
- Never make online connectivity a requirement for core functionality that can work offline

### 2. 🔒 Privacy by Design

**We believe your data belongs to you. No tracking, no surveillance, no data collection.**

Analytics and trackers may be useful for understanding project usage and focusing on what users value, but this obsession with data doesn't account for the cost of trust lost from users and the legal obligations it may carry. By completely abstaining from ANY form of tracking, we aim to create an intangible value for our brand: unrestricted trust.

**Guidelines:**
- Don't collect ANY data
- No analytics, no trackers, no telemetry of any kind
- Store data securely and locally only
- Provide clear privacy controls
- Default to the most private option
- Be transparent about data usage (or lack thereof)
- Never compromise user privacy for convenience or metrics

### 3. 🧑‍💻👨🏾‍💻👩‍💻 Open Source

**Transparency builds trust. All our code is open source and auditable.**

To build trust, it's essential that our users can know what's happening in the projects we develop. Open source is non-negotiable. The GPL v3 license with restrictions (see license template) should always be prioritized.

**Guidelines:**
- Write readable, maintainable code
- Document your work thoroughly
- Use open source dependencies when possible
- Avoid proprietary or restrictive licenses
- All code must be auditable and transparent
- Make it easy for users to verify what our software does

### 4. 🎯 Focused Utility

**No bloat, no ads, no unnecessary "smart" features. Just fast, efficient software that does what it is supposed to do.**

The concept of Focused Utility means always keeping in mind that any feature in our projects must serve the project itself, not exist for its own sake. Incorporating a tool just because similar apps do it is not something that prioritizes the project's interest. Remember that any implementation in development has a cost: unpredictable effects, performance impact, conflicts with other packages/devices. This cost can never exceed the benefit it provides to the user.

**Guidelines:**
- Question whether a feature truly serves users or just adds complexity
- Avoid feature creep and bloat
- Prioritize performance and efficiency
- Consider the maintenance cost of every addition
- Say no to features that don't align with the project's core purpose
- No ads, no dark patterns, no unnecessary "smart" features

### 5. 🤝 Community

**Built by the community, for the community. No corporate interests or profit motives.**

Since we don't have trackers, our only way to understand what our community needs is by talking to them. The goal of our collective is not just to develop these projects but also to create a culture that values greater knowledge of what we consume digitally. In other words, to remove the alienation between user and product and build bridges between developers and those who benefit from the project. Fostering the community, not just among developers, is a pillar and objective of Offline Labs.

**Guidelines:**
- Engage actively with the community
- Listen to user feedback and needs
- Help educate users about the software they use
- Build bridges between developers and users
- Foster an inclusive, welcoming environment
- Share knowledge and help others learn
- Remember: we serve the community, not shareholders or advertisers

### 6. 💪 User Empowerment

**Full control, no unnecessary limits. Our apps let you customize and optimize your experience as you see fit.**

We believe that by understanding the product, users don't need excessive guardrails. We should avoid artificially limiting any functionality in our projects just because we think users won't know what to do with it.

**Guidelines:**
- Give users full control over their experience
- Don't artificially limit features "for their own good"
- Provide customization and configuration options
- Trust users to make their own decisions
- Offer power user features without hiding them
- Make advanced features discoverable but not overwhelming
- Respect user agency and choice

---

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
- Explain why this enhancement would be useful and how it aligns with our core principles
- List any similar features in other applications if applicable
- Consider the cost vs. benefit (see Principle 4: Focused Utility)

### 📝 Documentation

- Fix typos or clarify existing documentation
- Add missing documentation
- Translate documentation
- Create tutorials or examples
- Help users understand and get the most from our software

### 💻 Code Contributions

- Pick an issue labeled `good first issue` if you're new
- Look for issues labeled `help wanted`
- Propose new features or improvements (ensuring they align with our principles)
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
4. **Make your changes** following our development guidelines and core principles
5. **Test your changes** thoroughly (including offline functionality)
6. **Commit your changes** with clear, descriptive messages
7. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
8. **Open a Pull Request** to the main repository

## Development Guidelines

### Alignment with Core Principles

Before writing any code, ask yourself:

1. **Does this work offline?** If not, is there a valid reason why not?
2. **Does this respect privacy?** Am I sure I'm not collecting ANY data?
3. **Is this transparent?** Can users audit and understand what this does?
4. **Is this truly useful?** Does the benefit outweigh the cost and complexity?
5. **Does this serve the community?** Am I building what users need, not what I think is cool?
6. **Does this empower users?** Am I giving control, or taking it away?

If you can't answer these questions confidently, reconsider your approach.

### General Guidelines

- **Follow coding style guidelines**: Maintain consistency with existing code
- **Write clear, documented code**: Use comments where necessary, write self-documenting code
- **Test your changes thoroughly**: Include unit tests, integration tests, and manual testing
- **Keep commits focused and atomic**: One logical change per commit
- **Be respectful and inclusive**: Follow our Code of Conduct
- **Help others learn and grow**: Review PRs constructively, answer questions patiently
- **Share knowledge and experience**: Contribute to documentation and discussions

## Coding Standards

- **Clean code**: Follow existing style, use meaningful names, keep functions focused
- **Documentation**: Add docstrings, update README, comment complex logic
- **Testing**: Write tests for new features, ensure existing tests pass, **test offline functionality thoroughly**
- **Performance**: Consider implications of changes, optimize for offline usage, remember every feature has a cost
- **Security**: Never commit secrets, sanitize input, follow best practices, report issues privately
- **Privacy**: No analytics, no tracking, no telemetry, no external data collection of any kind

## Commit Guidelines

Use clear, descriptive commit messages:

```
type: Brief summary (50 characters or less)

Optional detailed explanation. Reference issues with "Fixes #123".
```

**Types**: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

**Example**:
```
feat: Add offline mode indicator to status bar

Implements visual indicator showing connection status.
All functionality remains available offline.

Fixes #42
```

## Pull Request Process

### Before Submitting

Ensure your PR:
- Follows style guidelines and passes all tests
- Includes updated documentation
- Respects all 6 core principles
- Works offline (if applicable)
- Contains no tracking or data collection

### PR Description

Include:
- What the PR does and why
- How it aligns with our principles
- How it was tested
- Screenshots (for UI changes)
- Related issues ("Fixes #123")

### Checklist

- [ ] Code follows project style and is well-commented
- [ ] Documentation updated
- [ ] Tests added/updated and passing
- [ ] **Offline functionality verified**
- [ ] **No tracking/analytics added**
- [ ] Open source dependencies only
- [ ] Feature serves the project purpose

## Community

### Getting Help

- **Discussions**: Ask questions in GitHub Discussions
- **Issues**: Report bugs or request features
- **Documentation**: Check project docs and README files

### Reviewing PRs

- Be constructive and respectful
- Consider alignment with core principles
- Help others learn

### Staying Connected

- Participate in discussions
- Help answer questions
- Share knowledge and experience
- Help bridge developers and users

## Recognition

Contributors are listed in project documentation, mentioned in release notes, and appreciated by the community.

## Questions?

Open an issue, start a discussion, or reach out to maintainers. We're here to help!

Thank you for contributing to Offline Labs! Together, we're building a better, more private, and open future.
