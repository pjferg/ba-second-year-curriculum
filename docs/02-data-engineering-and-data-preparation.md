# Data Engineering & Data Preparation

> **Would an analyst embedded in finance, marketing, operations, HR, consulting, healthcare or another business function plausibly need this capability to turn an analysis into something reliable that colleagues can actually use?**

Data Engineering & Data Preparation develops students' ability to **build reliable analytical data pipelines**.

The subject begins from the reality that the data required to solve business problems rarely arrive as a single clean dataset. They are distributed across files, databases, APIs and organisational systems; recorded at different levels of observation; updated over time; and subject to errors, inconsistencies and changing requirements.

The organising workflow is:

**business problem → data sources → ingestion → validation → transformation → integration → storage → analysis-ready data → recurring pipeline**

## Learning through business problems

The subject should be organised around substantial business problems rather than disconnected technical topics. A problem might require students to combine transaction records stored in a database, customer information received as files, and external information obtained through an API. The analytical objective provides the reason to assemble these sources into a coherent data pipeline.

This creates natural reasons to introduce increasingly sophisticated tools.

Students use **SQL** because important organisational data reside in databases. They use **APIs** because relevant information must be obtained from other systems. R remains a core analytical language, while **Python** can be introduced where its ecosystem provides a genuine advantage.

As projects become larger, students encounter the limitations of long, sequential scripts. Functions and **modular software design** allow pipelines to be decomposed into reusable components with clearly defined inputs and outputs. Sensible directory structures, naming conventions, documentation and consistent coding practices make these projects understandable to other people.

**Git and GitHub** become the normal environment for development rather than separate topics to be learned. Students progressively encounter branches, pull requests and code review as projects become collaborative.

## From a script to a reliable pipeline

The central progression is from code that successfully transforms a dataset once to a process that can be trusted to do so repeatedly.

Students therefore encounter **data validation, assertions and unit testing** because pipelines must cope with new and potentially malformed data. Dependency and environment management address the problem of analytical code behaving differently across computers. Configuration and environment variables separate code from settings and credentials.

Basic **Bash and command-line workflows** provide another mechanism for running and connecting analytical tasks.

Once pipelines are expected to run regularly, **workflow scheduling and automation** arise naturally. Students then confront a further operational question: *How do we know whether the pipeline actually worked?* This provides a practical introduction to error handling, logging and basic monitoring.

Containers and **Docker** address the need to execute a pipeline consistently in different environments. Basic continuous integration can allow tests and other checks to run automatically when code changes.

Cloud infrastructure such as **AWS or Azure** can provide practical exposure to remote storage, databases and computation, while introducing responsible management of credentials, secrets and permissions.

## Intended outcome

The analytical purpose of the data remains central throughout. Students continually ask what data are required to answer the business question, how they should be represented and related, and whether the resulting pipeline faithfully captures the underlying business processes.

By the end of the subject, students should have progressed from:

**“I can clean and manipulate a dataset”**

to:

**“I can build, test and operate a reproducible data pipeline that produces the data needed to solve this business problem.”**

This provides the engineering foundation for building analytical products in Applied Analytics for Business Decision Making.
