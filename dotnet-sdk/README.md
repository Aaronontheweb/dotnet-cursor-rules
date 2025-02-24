# .NET SDK Management Rules

This directory contains rules for managing .NET solutions with consistent SDK versions, build configurations, and dependencies.

## [Solution Management](solution-management.mdc)

Use this when you're:
- Setting up a new .NET solution
- Implementing consistent build properties across projects
- Managing NuGet package versions centrally
- Need to ensure consistent SDK versions across development environments

These rules help establish:
- SDK version control via `global.json`
- Shared metadata via `Directory.Build.props`
- Centralized package management via `Directory.Packages.props`
- Secure package sources via `nuget.config`

## [Dependency Management](dependency-management.mdc)

Use this when you're:
- Installing or updating NuGet packages
- Evaluating package security and licenses
- Setting up automated dependency management
- Implementing dependency scanning in CI/CD

These rules help ensure:
- Safe and consistent package management via CLI
- License compliance and security scanning
- Version management best practices
- Automated vulnerability detection

## Related Rules

- For publishing your own NuGet packages, see the [NuGet Package Publishing Rules](../nuget-packages/README.md)
- For CI/CD integration, see the [CI/CD Rules](../ci-cd/README.md)
- For .NET tool management, see the [.NET Tool Rules](../dotnet-tools/README.md) 