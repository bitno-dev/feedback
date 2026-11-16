# Bitno

**Lightweight, private and secure developer tools for VS Code. Built by a developer, for developers.**

This repository is where you report bugs, ask for features and ask questions about any Bitno extension. It holds no source code.

## Extensions

| Extension | What it does |
| --- | --- |
| [Services](https://marketplace.visualstudio.com/items?itemName=bitno.services-by-bitno) | Docker, Kubernetes, Postgres, Cassandra, Kafka, Redis, MongoDB, Elasticsearch, S3 and SSH hosts in one panel next to Terminal |
| [Language Server for Java](https://marketplace.visualstudio.com/items?itemName=bitno.ls-java-by-bitno) | Java on Gradle builds, analyzed by javac in-process |
| [Language Server for Kotlin](https://marketplace.visualstudio.com/items?itemName=bitno.ls-kotlin-by-bitno) | Kotlin on Gradle builds |
| [Bitno Pack for Java](https://marketplace.visualstudio.com/items?itemName=bitno.java-pack-by-bitno) | Java and Gradle in one install |
| [Language Server for Gradle](https://marketplace.visualstudio.com/items?itemName=bitno.ls-gradle-by-bitno) | Groovy and Kotlin DSL build scripts and version catalogs |
| [Language Server for Maven](https://marketplace.visualstudio.com/items?itemName=bitno.ls-maven-by-bitno) | `pom.xml` completion and documentation |
| [Language Server for Bash](https://marketplace.visualstudio.com/items?itemName=bitno.ls-bash-by-bitno) | ShellCheck and shfmt built in |
| [Markdown Language Server](https://marketplace.visualstudio.com/items?itemName=bitno.ls-markdown-by-bitno) | dprint formatting and markdownlint, set to agree |
| [YAML Language Server](https://marketplace.visualstudio.com/items?itemName=bitno.ls-yaml-by-bitno) | Red Hat's yaml-language-server, without telemetry |
| [TOML Language Server](https://marketplace.visualstudio.com/items?itemName=bitno.ls-toml-by-bitno) | taplo built in |
| [EditorConfig](https://marketplace.visualstudio.com/items?itemName=bitno.editorconfig-by-bitno) | EditorConfig made for monorepos |
| [Convert](https://marketplace.visualstudio.com/items?itemName=bitno.convert-by-bitno) | Base64, JWT, JSON, case and more on the selection, without leaving the editor |
| [Paths](https://marketplace.visualstudio.com/items?itemName=bitno.paths-by-bitno) | Path completion and clickable paths in any string |

Every extension is in early development: expect missing features, rough edges and breaking changes between versions.

## Private by design

No telemetry, no account, no cloud, in every extension. Each extension's Marketplace page lists exactly what it contacts over the network, and Bash, Markdown, Maven, EditorConfig, Convert and Paths contact nothing at all.

## Report a bug or ask for a feature

[Open an issue](https://github.com/bitno-dev/feedback/issues/new/choose) and pick the extension it's about. Blunt feedback is welcome: what's missing, what breaks, what you'd use next.

- **Bug:** the extension's version, your VS Code version and OS, and steps to reproduce it. The extension's log helps most; remove paths, hostnames and anything secret before you paste it.
- **Feature:** the problem you want solved, before the solution you have in mind.
- **Question or idea:** [Discussions](https://github.com/bitno-dev/feedback/discussions).
- **Security issue:** report it privately, never in an issue; see [SECURITY.md](SECURITY.md).
