# Vostok devtools

This module contains various tools, helpers and guidelines serving to ease/automate the development of Vostok .NET libraries:

* [Library development conventions](library-dev-conventions/conventions.md) to govern dev and CI processes (also for [source-only libs](library-dev-conventions/src-libs-conventions.md)).
* [Checklist](library-dev-conventions/how-to-create-new-library.md) for developers creating new libraries.
* [Launchpad](launchpad) tool to ease bootstrapping of new repositories.
* [Launchpad template](launchpad-templates/library-ordinary) for Vostok ordinary libraries
* [Launchpad template](launchpad-templates/library-source) for Vostok source libraries
* [C# code style](code-style-csharp) to keep the code clean and homogeneous.
* [GitCommit2AssemblyTitle](git-commit-to-assembly-title) build target to enrich assemblies with Git info.
* [dotnetcementrefs](dotnetcementrefs) CLI tool for .NET Core 2.1 to convert Cement references into NuGet package references.
* [dotnetversionsuffix](dotnetversionsuffix) CLI tool for .NET Core 2.1 to patch project versions during CI.
