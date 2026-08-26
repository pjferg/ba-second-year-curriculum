# Version control

This repository versions authored source and the configuration needed to reproduce
the work. Generated files, local machine state, data and rendered outputs are not
committed.

## What to commit

- Source documents and code, such as Markdown, Quarto, R, Python, SQL and shell files.
- Project configuration, tests and automation definitions.
- Dependency manifests and lockfiles used to reproduce the environment.
- Small, hand-authored assets that cannot be regenerated.

Do not commit rendered documents, build directories, data extracts, analysis results,
package libraries, virtual environments, caches, credentials or editor settings. Add
new classes of generated files to `.gitignore` rather than repeatedly removing them
from Git.

## Workflow

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

## Outputs

Build and render commands should write to an ignored output location. If an output
must be distributed, publish it through an appropriate release or shared-file system
rather than storing it in Git.

Never force-add an ignored file without first deciding whether the ignore policy
needs to change for the whole repository.
