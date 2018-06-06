## GitIgnore File
This file is necessary to keep unwanted files out of source control. It is one of the more trivial Solution Fitness Parameters, but an important one. Adding a .gitignore file often specifies the "second" developer of a system beginning to work on the system. It may seem like unneeded ceremony, but .gitignore files clean up repositories considerably and reduce the size of repositories.

This can also curb bad habits in codebases. For example, the inclusion of a .gitignore file will often lead to the exclusion of .DLL files in a .NET repository, which can lead to errors in the codebase if it relied on direct .DLL references, rather than using NuGet.

*Acceptance Criteria* - presence of a .GitIgnore file to omit unnecessary files from repositories. 