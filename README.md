# blueprint-repo-blueprints

> The language-agnostic grandparent template from which all other blueprint repos are derived.

## What Is This?

This is a **GitHub template repository** that provides the foundational directory structure, documentation, and configuration shared by all downstream blueprint repositories. It contains no language-specific content — only the universal scaffolding that every project needs.

## How to Use This Template

1. Click the **"Use this template"** button at the top of the repository page on GitHub.
2. Choose a name for your new repository (e.g., `blueprint-python`, `blueprint-node`).
3. Clone your new repository and begin adding language-specific content.

For more details on GitHub template repositories, see the [official documentation](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository).

## What's Included

| Path | Purpose |
| :--- | :--- |
| `meta/adr/` | Architecture Decision Records — the logbook of *why* decisions were made |
| `meta/plans/` | Project plans and roadmaps |
| `docs-src/` | Source files for generated documentation (e.g., MkDocs) |
| `scripts/` | Utility and automation scripts |
| `.github/` | GitHub-specific configuration (issue templates, PR templates) |

### Key Files

- **`LICENSE.md`** — GNU General Public License v3.0
- **`CODE_OF_CONDUCT.md`** — Contributor Covenant Code of Conduct
- **`SECURITY.md`** — Security policy and vulnerability reporting
- **`CONTRIBUTING.md`** — Guidelines for contributing to the project
- **`meta/adr/TEMPLATE.md`** — Template for new Architecture Decision Records
- **`meta/adr/ADR-001-use_adrs.md`** — The founding ADR: use ADRs to document decisions

## Design Principles

- **Minimal by design.** Downstream blueprints add language-specific tooling, CI/CD, and dependencies.
- **Documentation-first.** Every significant decision is captured in an ADR.
- **AI-friendly.** The structure and conventions are designed to work well with AI-assisted development workflows.

## License

This project is licensed under the [GNU General Public License v3.0](./LICENSE.md).
