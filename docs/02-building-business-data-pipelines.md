---
header-includes:
  - \usepackage{amssymb}
---

# CMCE20001 - Building Business Data Pipelines {.unnumbered}

## Subject purpose

This subject develops students' ability to build reliable data pipelines. Students identify required data, acquire and integrate multiple sources, and produce validated analysis-ready datasets that update as new data arrive.

This subject complements CMCE20002 - Building Business Analytics Solutions, and either may be taken first. It starts from raw business data and uses SQL and Python to build reliable pipelines; CMCE20002 starts from prepared data and uses R and Shiny to build decision tools.

## Subject coverage

### Data requirements and representation

- Translate business questions into data requirements, units of observation and appropriate structures; interpret entity-relationship diagrams, keys, relationships and table grain.
- Identify missing, duplicated, inconsistent, invalid, stale or selectively observed data and assess fitness for the intended purpose.

### Data acquisition and storage

- Query relational databases using SQL, including filtering, aggregation, joins and window operations.
- Acquire structured and semi-structured data from files and web APIs, including pagination, authentication and response handling.
- Compare common operational and analytical data systems; select appropriate storage and preserve schemas, keys and metadata.
- Manage credentials, secrets, authentication and permissions responsibly.

### Transformation, integration and temporal data

- Transfer R/dplyr concepts into SQL and Python/pandas, using Python to ingest, clean, standardise, aggregate, join and reshape data.
- Combine sources recorded at different levels of observation and resolve incompatible identifiers, formats and definitions.
- Represent, resample and aggregate time-indexed data, including events, time zones and irregular observations; construct longitudinal or panel-like datasets.
- Design repeatable transformations that preserve provenance and safely handle incremental data, repeated execution and changing source schemas.

### Reliable pipeline development

- Decompose pipelines into functions and modules, and organise Python projects using consistent structures, naming, configuration and documentation.
- Validate inputs, intermediate results and outputs using assertions, schema checks and other data-quality tests.
- Write unit and basic integration tests.
- Use Git and GitHub for version control and collaborative review.
- Record and reproduce software dependencies and execution environments.

### Pipeline operation

- Run, connect, automate and schedule tasks using command-line and shell workflows.
- Implement error handling, logging and basic monitoring that make failures visible and diagnosable.
- Use continuous integration to run checks when code changes, and package a pipeline with Docker for execution using cloud storage, databases or computation.

## Technical capabilities covered

|  |  |
|:--|:--|
| $\checkmark$ Programming and query languages | $\checkmark$ Version control and collaboration |
| $\checkmark$ Software design and coding practices | $\checkmark$ Testing and quality assurance |
| $\checkmark$ Documentation and reproducibility | $\checkmark$ Command line and scripting |
| $\checkmark$ Data systems and integration | $\checkmark$ Deployment and operations |
| $\checkmark$ Cloud infrastructure | $\checkmark$ Security fundamentals |

## Intended outcome

By the end of the subject, students should be able to build, test and operate a reproducible pipeline combining files, databases and APIs to produce trustworthy business data. They should use SQL and Python/pandas effectively, reason about data architecture and temporal structure, assess quality, collaborate, diagnose failures and deliver documented data another analyst can use.
