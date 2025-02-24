# NuGet Package Publishing Rules

This directory contains rules and best practices for publishing NuGet packages.

## Files

- `nuget-package-publishing.mdc`: Contains comprehensive rules for publishing NuGet packages, including:
  - License configuration best practices
  - Package documentation requirements
  - Metadata organization guidelines
  - Source debugging and symbol package setup
  - Dependency management recommendations
  - Versioning conventions
  - Build and pack commands
  - Quality assurance checklist

## When to Use These Rules

These rules should be followed when:
- Creating new NuGet packages
- Updating existing package configurations
- Setting up CI/CD pipelines for package publishing
- Reviewing package metadata and configuration
- Implementing source debugging capabilities
- Managing package dependencies

## Related Rules

- See the [.NET Tool Rules](../dotnet-tools/README.md) for related guidance on:
  - [Publishing .NET Tools](../dotnet-tools/publishing-dotnettool.mdc)
  - [Consuming .NET Tools](../dotnet-tools/consuming-dotnettool.mdc)
- CI/CD related configurations can be found in the [CI/CD Rules](../ci-cd/README.md) directory:
  - [.NET Build System Rules](../ci-cd/dotnet-build.mdc) - Includes pipeline configuration for package builds
  - [Code Signing Rules](../ci-cd/code-signing.mdc) - Important for signing NuGet packages 