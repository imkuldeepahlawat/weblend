# Contributing to weblend

Thank you for your interest in contributing to weblend! This guide will help you get started.

## Quick Start

1. Fork and clone the repo:
   ```bash
   git clone https://github.com/imkuldeepahlawat/weblend.git
   cd weblend
   ```

2. Install and run:
   ```bash
   yarn install
   yarn dev
   ```

3. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature
   ```

4. Make changes, test, and submit a PR

## Git Hooks Setup

We use Husky for Git hooks. After installing dependencies, run:
```bash
yarn husky install
```

### Pre-commit Checks
Before each commit, the following checks run automatically:
- Code formatting with Prettier
- TypeScript type checking
- Build verification
- Test suite

To manually run pre-commit checks:
```bash
yarn precommit
```

## Guidelines

### Branch Naming
Follow this pattern: `type/description`
- `feature/` - New features
- `fix/` - Bug fixes
- `docs/` - Documentation changes
- `refactor/` - Code refactoring
- `test/` - Test additions/changes
- `chore/` - Build process, tooling changes

Examples:
- `feature/3d-modeling-tools`
- `fix/camera-controls`
- `docs/installation-guide`

### Commit Messages
Format: `type(scope): description`

Types:
- `feat` - New feature
- `fix` - Bug fix
- `docs` - Documentation
- `style` - Formatting, missing semicolons, etc
- `refactor` - Code refactoring
- `test` - Test related
- `chore` - Build process, tooling

Examples:
- `feat(3d): add basic mesh creation`
- `fix(camera): correct orbit controls`
- `docs(readme): update installation steps`

### Code Style
- TypeScript + React functional components
- Small, focused components
- Meaningful commit messages
- Tests for new features
- Prettier for code formatting
- ESLint for code quality

### 3D Development
- Use Three.js for 3D rendering
- Follow Blender-like conventions
- Optimize for performance
- Document complex 3D operations

### Pull Requests
- Keep changes focused
- Include tests
- Update docs if needed
- Ensure all tests pass
- Verify build passes
- Format code with Prettier

### Issues
When reporting issues, include:
- Steps to reproduce
- Expected vs actual behavior
- Browser/OS version
- Error messages

Need help? Open an issue! 