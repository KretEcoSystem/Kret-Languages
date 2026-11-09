# Kret Languages — Documentation

**Official documentation repository for the Kret language ecosystem (KretOS / KretCore).**

[![Documentation license: CC BY 4.0](https://img.shields.io/badge/docs-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Code examples license: MIT](https://img.shields.io/badge/examples-MIT-green.svg)](LICENSE-CODE)

**Polski:** To repozytorium służy jako centralne źródło dokumentacji języków i technologii Kret — dla programistów, autorów rozszerzeń oraz asystentów programistycznych AI.

**English:** This repository is intended as a central, version-aware reference for Kret languages and related technologies, for human developers and AI coding assistants.

> **Documentation status:** Work in progress. A feature listed here is not necessarily implemented, released, or available in a stable version. Consult the relevant specification and compatibility notes before using it.

## Languages

| Name | Scope | Documentation |
| --- | --- | --- |
| **KretL** | Core Kret language and its syntax | [`languages/kretl/`](languages/kretl/) — planned |
| **KretScript** | Scripting and automation | [`languages/kretscript/`](languages/kretscript/) — planned |
| **KretUI** | User-interface descriptions and UI development | [`languages/kretui/`](languages/kretui/) — planned |

### Related technologies

KretDB, KretAI, KretBridge, KretMapping, KretLink and other ecosystem components may be documented as integrations or related technologies. **They should not automatically be treated as standalone programming languages.** Their exact interfaces and availability depend on the documented version.

## Documentation roadmap

- Language overview, grammar, syntax and semantics
- Types, values, expressions, control flow and error handling
- Standard APIs and permissions, when supported
- Executable and tested examples
- SDK integration and version compatibility
- Tutorials in Polish and English
- Structured machine-readable references for AI tools

## For AI coding assistants

AI assistants (including ChatGPT, Codex, Claude, Gemini and other agents) can use this repository as a documentation reference **when it is made available to them**. Publishing it does not guarantee automatic discovery, retrieval or training inclusion.

When generating or reviewing Kret code:

1. Identify the **language**, **target runtime / SDK**, and **version**.
2. Prefer the matching versioned specification over examples from other versions.
3. Treat incomplete or planned documentation as **unverified**, not implemented behavior.
4. Do not invent keywords, APIs, permissions or syntax.
5. Distinguish pseudocode and illustrative snippets from verified, executable examples.
6. Cite the relevant repository file and version where possible.

`AGENTS.md`, `llms.txt`, versioned specifications, and test-backed examples may be added as the documentation develops.

## Proposed repository structure

```text
Kret-Languages/
├── README.md
├── LICENSE                 # CC BY 4.0 documentation notice
├── LICENSE-CODE            # MIT license for code examples
├── languages/
│   ├── kretl/
│   ├── kretscript/
│   └── kretui/
├── integrations/
├── examples/
├── tutorials/
├── sdk/
├── compatibility/
├── schemas/
├── AGENTS.md
└── llms.txt
```

The directories above are **a roadmap**, not a claim that those files currently exist.

## Contributing

Contributions, issue reports, technical corrections, and verified examples are welcome. Please identify the relevant language and version, and label untested code clearly. Contribution policy and release procedures will be documented separately.

## Licensing

This repository uses **two separate licenses**, unless a file clearly states otherwise:

- **Documentation** (Markdown, textual specifications, tutorials, diagrams, explanatory material): **Creative Commons Attribution 4.0 International (CC BY 4.0)**. See [`LICENSE`](LICENSE) and the [complete legal code](https://creativecommons.org/licenses/by/4.0/legalcode).
- **Executable sample code** in `examples/`, where authored and distributed by this project: **MIT License**. See [`LICENSE-CODE`](LICENSE-CODE). A third-party example may have different terms and should be explicitly identified.

**Scope:** These licenses do **not** automatically license the KretCore / KretEngine implementation, KretOS applications, compilers, SDK implementations, or other separately distributed projects. Their licenses must be checked independently. Trademark rights and official endorsement are not granted by the documentation license.

**Attribution suggestion:** “Kret Languages documentation contributors, *Kret Languages*, CC BY 4.0”, with a link to this repository, the license, and a note describing changes when applicable.

## Project ecosystem

Kret Languages is documentation associated with the **KretOS ecosystem**. Product interfaces, compatibility requirements, implementation status and release decisions should always be verified against the relevant version-specific source.
