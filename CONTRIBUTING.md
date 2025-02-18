# Contributing to Cursor AI Rules

Thank you for your interest in contributing to the Cursor AI Rules repository! This document provides guidelines and information about contributing to this repository.

## Types of Contributions

We welcome the following types of contributions:

1. New C# style rules
2. New F# style rules
3. Library-specific rules for .NET libraries
4. Improvements to existing rules
5. Documentation improvements

## How to Contribute

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes following the guidelines below
4. Submit a pull request

## Guidelines for Rule Contributions

### General Guidelines

- Each rule should be in its own `.mdc` file
- Rules should be placed in the appropriate directory:
  - C# rules go in the `csharp/` directory
  - F# rules go in the `fsharp/` directory
  - Library-specific rules go in their respective library directories

### Rule Documentation

Each rule should include:

1. A clear description of what the rule enforces
2. Examples of correct ("do") and incorrect ("don't") code
3. Rationale for why the rule is beneficial
4. Any exceptions or special cases where the rule might not apply

### Directory Structure

```
rule-category/
├── README.md           # Overview of rules in this category
└── specific-rule.mdc   # Individual rule file
```

## Pull Request Process

1. Ensure your PR includes only one logical change (e.g., one new rule or one rule modification)
2. Update relevant documentation
3. Verify all links in markdown files are valid
4. Fill out the PR template completely

## Need Help?

If you need help or have questions:

1. Check existing issues and documentation
2. Open a new issue with your question
3. Tag it appropriately (question, help wanted, etc.)

## License

By contributing to this repository, you agree that your contributions will be licensed under the same license as the repository. 