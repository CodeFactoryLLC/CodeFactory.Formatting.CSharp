# CodeFactory.Formatting.CSharp
This open source project provides extended formatting for C# code output - intended for use by a CodeFactory automation template author.  The final output is published as a Nuget Package which makes available all of the formatting helpers to implementing authors.

## New to CodeFactory?
In the simplest terms, [CodeFactory](www.codefactory.software) is a real time software factory that is triggered from inside Visual Studio during the design and construction of software. CodeFactory allows for development staff to automate repetitive development tasks that consume much of a developer’s time.

Please see the following link for further information and guidance about the [CodeFactory Runtime](https://github.com/CodeFactoryLLC/CodeFactory) or the [CodeFactory SDK](https://www.nuget.org/packages/CodeFactorySDK/).

## Core purpose of this project
This project provides a series of formatting helpers that are organized by language, each of which makes it easier for an automation template author to emit code artifacts back into a project/solution.  Currently the project contains helpers for the following language and categories:
- C# Lanuguage
  - Attribute helpers
  - Class helpers
  - Enum helpers
  - Event helpers
  - Field helpers
  - Generic Parameter helpers
  - Interface helpers
  - Method helpers
  - Parameter default value helpers
  - Parameter helpers
  - Property helpers
  - Security helpers
  - SourceCode Formatter
  - Structure helpers
  - Type helpers
  - Documentation helpers
  - Namespace manager


## Known Limitations of this project
- Currently only has formatters for the .NET C# language
