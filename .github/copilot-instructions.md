# Copilot Instructions for Screening Repository

## Repository Overview

This is the screening repository for global nutrition systems. This repository is used to manage screening processes and related functionality.

## Project Conventions

### Code Style
- Follow language-specific best practices and idiomatic patterns
- Use clear, descriptive variable and function names
- Keep functions focused and single-purpose
- Add comments only when necessary to explain complex logic

### File Organization
- Keep related files organized in appropriate directories
- Use clear, descriptive file names
- Maintain consistent naming conventions across the project

### Version Control
- Write clear, concise commit messages
- Keep commits focused on a single logical change
- Reference issue numbers in commit messages when applicable

## Development Guidelines

### Making Changes
- Make minimal, focused changes that address the specific issue
- Ensure changes don't break existing functionality
- Update documentation when making significant changes
- Test changes before committing

### Code Quality
- Write clean, maintainable code
- Follow DRY (Don't Repeat Yourself) principles
- Handle errors appropriately
- Consider edge cases and validation

### Security
- Never commit secrets, API keys, or credentials
- Validate and sanitize user inputs
- Follow security best practices for the technology stack
- Be mindful of common vulnerabilities (XSS, SQL injection, etc.)

## Testing

### Test Practices
- Write tests for new functionality when test infrastructure exists
- Ensure existing tests pass before committing
- Test edge cases and error conditions
- Keep tests focused and maintainable

### Running Tests
- Check for existing test scripts in package.json, Makefile, or similar
- Run relevant tests after making changes
- Fix any test failures related to your changes

## Build and Deployment

### Building the Project
- Look for build scripts in the project configuration files
- Ensure the project builds successfully after changes
- Follow any existing build conventions

### Dependencies
- Keep dependencies up to date when appropriate
- Document any new dependencies added
- Use lock files to ensure reproducible builds

## Documentation

### Code Documentation
- Document public APIs and interfaces
- Keep README.md up to date
- Add inline comments for complex algorithms or business logic

### Change Documentation
- Update relevant documentation when making changes
- Keep documentation clear and concise
- Include examples where helpful

## Communication

### Issue and PR Guidelines
- Provide clear descriptions of changes in pull requests
- Reference related issues
- Respond to review comments promptly
- Use @mentions to tag relevant team members

## Additional Notes

- This repository is in early stages of development
- Conventions may evolve as the project grows
- When in doubt, follow established patterns in the existing codebase
- Consult with the team for architectural decisions
