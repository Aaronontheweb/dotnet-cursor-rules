# CI/CD Rules and Best Practices

This directory contains detailed rules and best practices for CI/CD processes in .NET projects. These rules are designed to ensure consistency and quality across our build and deployment processes, supporting both GitHub Actions and Azure DevOps pipelines.

## Available Rules

### [.NET Build System Rules](./dotnet-build.mdc)
Comprehensive guidelines for .NET build systems, covering:
- Core build philosophy and best practices
- Project structure and required files
- Build script organization
- Version management
- CI/CD pipeline configuration for both GitHub Actions and Azure DevOps
- Cross-platform build compatibility

This rule applies to solution files (`.sln`), project files (`.csproj`, `.fsproj`), build configuration files, and CI/CD pipeline definitions (`.github/workflows/*.yaml` and `.azure/*.yaml`).

### [Code Signing Rules](./code-signing.mdc)
Best practices and configuration guidelines for .NET code signing, including:
- SignClient configuration
- Security best practices
- CI/CD integration for code signing in both GitHub Actions and Azure DevOps
- Credential management
- Audit logging requirements

This rule applies to signing configuration files (`signsettings.json`, `appsettings.json`) and package files (`.nupkg`).

## Using These Rules

These rules are automatically enforced through Cursor when working with relevant files. The rules provide inline guidance and validation to ensure your build and deployment configurations follow our established best practices, regardless of whether you're using GitHub Actions or Azure DevOps as your CI/CD platform.

For more information about our CI/CD practices or to propose changes to these rules, please contact the DevOps team.

## Related Rules

- For NuGet package publishing best practices, see the [NuGet Package Publishing Rules](../nuget-packages/README.md)
- For .NET SDK management, see the [.NET SDK Management Rules](../dotnet-sdk/README.md)
- For .NET tool management, see the [.NET Tool Rules](../dotnet-tools/README.md) 