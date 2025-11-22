# Contributing Guidelines

Thank you for contributing to this project!

## Code Style

- **Python**: PEP 8 (enforced by ruff)
- **JavaScript/TypeScript**: Standard JS
- **Documentation**: Markdown with consistent formatting

## Pull Request Process

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Run tests and linters locally
4. Commit with conventional commits:
   - `feat:` for new features
   - `fix:` for bug fixes
   - `docs:` for documentation
   - `refactor:` for code refactoring
   - `test:` for test additions/changes
5. Push and create pull request
6. Ensure CI passes
7. Wait for review and address feedback

## Testing Requirements

- All new code must include tests
- Minimum 70% code coverage
- All tests must pass before merge

## Development Setup

```bash
# Clone the repository
git clone https://github.com/bryankaufman/[repo-name].git
cd [repo-name]

# Install dependencies (Python projects)
pip install -r requirements.txt
pip install -r requirements-dev.txt

# Install dependencies (Node.js projects)
npm install

# Run tests
pytest  # Python
npm test  # Node.js
```

## Code Review Standards

- Code must be readable and well-documented
- No breaking changes without major version bump
- Security implications must be considered
- HIPAA compliance maintained (for healthcare repos)

## Questions?

Feel free to open an issue for questions or discussion.
