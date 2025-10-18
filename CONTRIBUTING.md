# Contributing to BasicFist

Thank you for your interest in contributing!

## Development Process

1. **Fork and Clone**
   ```bash
   git clone https://github.com/BasicFist/<repo>.git
   cd <repo>
   ```

2. **Create Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Changes**
   - Follow code style guidelines
   - Add tests for new functionality
   - Update documentation

4. **Run Tests**
   ```bash
   # Python projects
   pytest
   ruff check .
   mypy .

   # TypeScript projects
   npm test
   npm run lint
   npm run type-check
   ```

5. **Commit Changes**
   ```bash
   git commit -m "feat: add new feature"
   ```

   Use conventional commits:
   - `feat:` New feature
   - `fix:` Bug fix
   - `docs:` Documentation
   - `refactor:` Code refactoring
   - `test:` Tests
   - `chore:` Maintenance

6. **Push and Create PR**
   ```bash
   git push origin feature/your-feature-name
   ```

   Then create a pull request on GitHub.

## Code Standards

### Python
- Use Ruff for linting and formatting
- Type hints required (MyPy strict mode)
- Docstrings for public functions

### TypeScript
- Use Prettier for formatting
- ESLint for linting
- Strict TypeScript config

## Questions?

Open an issue or discussion for any questions.
