# .github - Organization Configuration

This repository contains organization-wide templates, workflows, and configuration for the BasicFist organization.

## Contents

### Profile
- `profile/README.md` - Organization profile displayed on GitHub

### Workflow Templates
Reusable CI/CD workflow templates for projects:
- `python-ci.yml` - Python testing, linting, and type checking
- `node-ci.yml` - Node.js/TypeScript testing and building

### Organization Workflows
- `.github/workflows/publish-workflows.yml` - Validates and syncs workflow templates

## Usage

### For New Python Projects
1. Copy `workflow-templates/python-ci.yml` to `.github/workflows/ci.yml` in your project
2. Adjust Python versions and test commands as needed
3. Add `CODECOV_TOKEN` secret if using coverage reporting

### For New Node.js Projects
1. Copy `workflow-templates/node-ci.yml` to `.github/workflows/ci.yml` in your project
2. Adjust Node versions and build commands as needed
3. Ensure package.json has appropriate scripts (lint, test, build)

## Development

To add new workflow templates:
1. Create `.yml` file in `workflow-templates/`
2. Include comprehensive job definitions
3. Document required secrets and setup steps
4. Test with example project before committing

## Standards

All templates follow BasicFist organization standards:
- Automated quality checks (linting, type checking)
- Comprehensive testing with coverage reporting
- Multi-version matrix testing
- Clear naming and documentation
