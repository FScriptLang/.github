<p align="center">
  <img src="https://raw.githubusercontent.com/FScriptLang/FScript/refs/heads/main/FScript.png" alt="FScript logo" width="160">
</p>

# FScriptLang

**Script. Embed. Compile.**

FScript is a typed, functional scripting language inspired by F# and the ML family. Run standalone scripts, embed configurable rules in .NET and JavaScript applications, or compile programs to optimized .NET assemblies and native executables.

[Explore the documentation](https://fscript.magnusopera.io/) · [Try it in your browser](https://fscript.magnusopera.io/sandbox) · [Get started](https://fscript.magnusopera.io/manual/learn/quickstart)

## A small language with room to grow

- **Functional foundations:** type inference, immutable data, pattern matching, records, discriminated unions, and pipelines.
- **Application scripting:** expose typed host APIs and control the capabilities available to scripts.
- **Flexible execution:** use the interpreter and REPL, embed in .NET or JavaScript, or compile to .NET, Native AOT, and buildable C# projects.
- **Editor support:** write FScript in VS Code with diagnostics, completion, navigation, and debugging.

## Start scripting

Install the CLI as a .NET tool:

```sh
dotnet tool install --global MagnusOpera.FScript
```

Or install with Homebrew:

```sh
brew install magnusopera/tap/fscript
```

Save this as `hello.fss`:

```fsharp
let greet name = $"Hello, {name}!"

Console.writeLine (greet "FScript")
```

Run it with `fscript hello.fss`, or explore the language in the [browser sandbox](https://fscript.magnusopera.io/sandbox).

## Explore the projects

| Repository | What lives here |
| --- | --- |
| [FScript](https://github.com/FScriptLang/FScript) | Language, interpreter, compiler, runtime, CLI, language server, and debugger. |
| [FScript.Extensibility](https://github.com/FScriptLang/FScript.Extensibility) | Independent SDK for authors of typed host extensions. |
| [FScript.Numerics](https://github.com/FScriptLang/FScript.Numerics) | Numerical arrays, linear algebra, statistics, and machine learning for .NET and FScript. |
| [vscode-extension](https://github.com/FScriptLang/vscode-extension) | VS Code extension, syntax grammar, and editor integration. |
| [FScriptLang.github.io](https://github.com/FScriptLang/FScriptLang.github.io) | Website, tutorials, and language documentation. |

## Get involved

Try the [examples](https://github.com/FScriptLang/FScript/tree/main/samples), report a problem or suggest a feature in the relevant repository, or contribute code and documentation. Start with that repository's README and contributor instructions.

FScriptLang is part of [Magnus Opera](https://github.com/MagnusOpera). Package and publisher names retain the Magnus Opera identity, including `MagnusOpera.FScript` on NuGet and `@magnusopera/fscript` on npm.
