# .NET SDK Management Rules

This directory contains rules for managing .NET solutions with consistent SDK versions and build configurations.

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