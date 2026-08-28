# Business Analytics Major — Second-Year Curriculum Development

This repository contains working curriculum documents for the development of the second-year core of the Business Analytics major.

The current design is organised around a simple principle:

> **Would an analyst embedded in finance, marketing, operations, HR, consulting, healthcare or another business function plausibly need this capability to turn an analysis into something reliable that colleagues can actually use?**

The aim is to develop students who can build reliable, useful things with data that solve important business problems. Software development and operational capabilities are learned primarily through substantial analytics tasks rather than as isolated technical topics.

## Documents

- [`docs/01-software-development-and-operations.md`](docs/01-software-development-and-operations.md) — overarching philosophy and core technical capabilities.
- [`docs/02-building-business-data-pipelines.md`](docs/02-building-business-data-pipelines.md) — proposal for CMCE20001.
- [`docs/03-building-business-analytics-solutions.md`](docs/03-building-business-analytics-solutions.md) — proposal for CMCE20002.

## Complementary subjects

- **Building Business Data Pipelines:** build reliable pipelines from raw business data using SQL and Python.
- **Building Business Analytics Solutions:** build reliable decision tools from prepared data using R and Shiny.

Together, the subjects cover the path from raw data sources to a usable analytical product. They are designed so that students may take either subject first; each independently introduces the shared development practices it requires.

These are working design documents intended to evolve as the second-year curriculum is developed.

## Rendering

The curriculum documents render to PDF with [Quarto](https://quarto.org/). From the
repository root, run:

```bash
quarto render
```

The PDFs are written to the ignored `output/` directory. A TeX distribution is
required; Quarto's TinyTeX is sufficient.

## Version control

This repository versions authored source and the configuration needed to reproduce
the work. Generated files, local machine state, data and rendered outputs are not
committed.

### What to commit

- Source documents and code, such as Markdown, Quarto, R, Python, SQL and shell files.
- Project configuration, tests and automation definitions.
- Dependency manifests and lockfiles used to reproduce the environment.
- Small, hand-authored assets that cannot be regenerated.

Do not commit rendered documents, build directories, data extracts, analysis results,
package libraries, virtual environments, caches, credentials or editor settings. Add
new classes of generated files to `.gitignore` rather than repeatedly removing them
from Git.

### Workflow

The `main` branch is the current shared version of the curriculum.

1. Pull `main` before starting work.
2. For a substantial or collaborative change, create a short-lived branch with a
   descriptive name, such as `revise-data-engineering-outcomes`.
3. Make small, focused commits with imperative messages that explain the change,
   such as `Clarify data pipeline learning outcomes`.
4. Review `git status` and `git diff --check` before pushing.
5. Merge substantial changes through a pull request. Delete the branch after merging.

Small, low-risk corrections may be committed directly to `main` when nobody else is
editing the same material.

### Outputs

Build and render commands should write to an ignored output location. If an output
must be distributed, publish it through an appropriate release or shared-file system
rather than storing it in Git.

Never force-add an ignored file without first deciding whether the ignore policy
needs to change for the whole repository.
