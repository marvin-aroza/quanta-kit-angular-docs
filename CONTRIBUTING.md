# Contributing to QuantaKit Angular Docs

Thank you for your interest in contributing to QuantaKit Angular Docs! This documentation platform showcases and demonstrates the QuantaKit UI component library. This guide will help you get started with contributing to our repository.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Development Workflow](#development-workflow)
3. [Submitting Changes](#submitting-changes)
4. [Getting Help](#getting-help)
5. [Code of Conduct](#code-of-conduct)

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Node.js** (version 18 or 20 — align with package.json "engines" or Angular docs)
- **npm** (comes with Node.js)
- **Git**

### Cloning the Repository

1. Clone the repository directly to your local machine:

```bash
git clone https://github.com/marvin-aroza/quanta-kit-angular-docs.git
cd quanta-kit-angular-docs
```

### Setting Up the Development Environment

1. **Install Dependencies**

```bash
npm install
```

2. **Environment Configuration**

Currently, this project doesn't require specific environment variables. If any are needed in the future, they will be documented here.

3. **Running the Development Server**

```bash
npm start
```

This will start the Angular development server at `http://localhost:4200`. The application will automatically reload when you make changes to the source files.

4. **Running Tests**

```bash
# Run tests once
npm test

# Run tests in CI mode (for continuous integration)
npm run test:ci
```

5. **Building the Project**

```bash
# Build for production
npm run build

# Build and watch for changes
npm run watch
```

## Development Workflow

### Code Style and Best Practices

#### Angular Conventions
- Follow the [Angular Style Guide](https://angular.io/guide/styleguide)
- Use TypeScript strict mode
- Implement proper component lifecycle management
- Use reactive programming patterns with RxJS

#### Documentation-Specific Guidelines
- Ensure all component examples are working and up-to-date
- Include comprehensive code examples with clear explanations
- Use consistent styling and formatting across all documentation pages
- Test all interactive demos and examples thoroughly
- Maintain responsive design principles for all documentation content

#### Code Formatting
- We recommend using Prettier for code formatting; configuration is included in `package.json`.
- If you install Prettier and configure Husky + lint-staged, commits can be auto-formatted. (This repository currently has Husky hooks but no hook that runs Prettier.)

#### Testing Guidelines
- Write unit tests for all new components and services
- Test all documentation examples and interactive demos
- Maintain or improve code coverage
- Use Angular Testing Utilities and Jasmine/Karma
- Test files should be named `*.spec.ts`

#### Documentation Standards
- Document all public APIs using JSDoc comments
- Update README.md if you add new features or sections
- Include inline comments for complex logic
- Ensure all code examples are functional and tested
- Update this CONTRIBUTING.md if you change the development process

### Branch Naming Convention

Create branches using the following format:

```
<type>/<ticket-number>-<brief-description>
```

**Examples:**
- `feat/qkd123-component-showcase-page`
- `fix/qkd456-demo-interaction-bug`
- `docs/qkd789-api-reference-update`

**Types:**
- `feat` - New features or documentation sections
- `fix` - Bug fixes in demos or documentation
- `docs` - Documentation content updates
- `style` - Code style changes (formatting, etc.)
- `refactor` - Code refactoring
- `test` - Adding or updating tests
- `chore` - Maintenance tasks

## Submitting Changes

### Commit Message Format

Follow the conventional commit format:

```
<type>(<scope>): <description>

[optional body]

[optional footer(s)]
```

**Structure:**
- **type**: The type of change (feat, fix, docs, style, refactor, test, chore)
- **scope**: The ticket number (e.g., QKD123)
- **description**: A brief description of the change

**Examples:**
```
feat(QKD123): add button component showcase page

fix(QKD456): resolve interactive demo scroll issue

docs(QKD789): update installation guide with new examples

style(QKD101): format documentation components according to prettier rules

refactor(QKD202): optimize component demo loading performance

test(QKD303): add unit tests for documentation navigation
```

### Pull Request Process

1. **Pull latest changes** (ensure you're working with the latest code from the default `main` branch):
```bash
git checkout main
git pull origin main
```

2. **Create and switch to your feature branch**:
```bash
git checkout -b feat/qkd123-your-feature-description
```

3. **Make your changes and commit**:
```bash
git add .
git commit -m "feat(QKD123): add your feature description"
```

4. **Push to the repository**:
```bash
git push --set-upstream origin feat/qkd123-your-feature-description
```

5. **Create a Pull Request**:
   - Navigate to the repository on GitHub
   - Click "New Pull Request"
   - Select your branch and target the `main` branch (default branch)
   - Fill out the PR template with the required information

### Pull Request Requirements

Your PR description should include:

1. **Task Description**: What does this PR accomplish?
2. **Changes Made**: List the key changes to documentation or demos
3. **Testing**: How was this tested? Include screenshots of new/updated demos
4. **Screenshots**: Before/after screenshots of documentation changes
5. **Breaking Changes**: Note any breaking changes to examples or APIs
6. **Related Issues**: Reference any related issues or tickets

**PR Title Format:**
```
[QKD123] Brief description of the change
```

**Example PR Description:**
```markdown
## Task Description
Adds comprehensive showcase page for the Button component with interactive demos and usage examples.

## Changes Made
- Created new button showcase component with multiple variants
- Added interactive demos for different button states
- Implemented code examples with syntax highlighting
- Updated navigation to include button component section

## Testing
- Tested all button variants and interactions
- Verified responsive behavior on mobile/tablet
- Validated all code examples are functional
- Screenshots attached showing new showcase page

## Related Issues
Closes #QKD123
```

### Review Process

1. All PRs require at least one approval from a maintainer
2. All tests must pass
3. All documentation examples must be functional
4. Code coverage should not decrease
5. Follow-up on any requested changes promptly

## Getting Help

### Documentation
- [Angular Documentation](https://angular.io/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [QuantaKit Component Library](../quanta-kit-angular)
- [Project README](./README.md)

### Community Support
- Create an issue for bugs, documentation improvements, or feature requests
- Join discussions in existing issues
- Reach out to maintainers for guidance on documentation structure

### Reporting Issues
When reporting issues, please include:
- Angular version
- Node.js version
- Browser and version
- Steps to reproduce the issue
- Expected vs actual behavior
- Screenshots of documentation problems
- Console errors (if any)

### Documentation Requests
When requesting new documentation:
- Specify which component or feature needs documentation
- Describe the target audience (beginners, advanced users, etc.)
- Suggest the type of examples needed
- Reference any existing documentation patterns to follow

## Code of Conduct

### Our Pledge

We pledge to make participation in our project a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Standards

Examples of behavior that contributes to creating a positive environment include:

- Using welcoming and inclusive language
- Being respectful of differing viewpoints and experiences
- Gracefully accepting constructive criticism
- Focusing on what is best for the community and documentation quality
- Showing empathy towards other community members
- Providing helpful and constructive feedback on documentation

Examples of unacceptable behavior include:

- The use of sexualized language or imagery
- Personal attacks or insulting/derogatory comments
- Public or private harassment
- Publishing others' private information without permission
- Other conduct which could reasonably be considered inappropriate

### Enforcement

Project maintainers are responsible for clarifying standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

Project maintainers have the right to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that are not aligned with this Code of Conduct.

### Reporting

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the project team. All complaints will be reviewed and investigated promptly and fairly.

---

Thank you for contributing to QuantaKit Angular Docs! Your contributions help make QuantaKit more accessible and easier to use for developers everywhere. 📚✨
