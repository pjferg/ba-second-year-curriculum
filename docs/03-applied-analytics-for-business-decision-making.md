# Applied Analytics for Business Decision Making

> **Would an analyst embedded in finance, marketing, operations, HR, consulting, healthcare or another business function plausibly need this capability to turn an analysis into something reliable that colleagues can actually use?**

Applied Analytics for Business Decision Making develops students' ability to **turn data and analytical methods into useful tools for business decisions**.

It builds on the data-engineering foundations of the preceding subject and shifts attention from constructing reliable analytical data to constructing, deploying and operating analytical solutions.

The organising workflow is:

**business problem → analytical approach → evaluation → analytical product → deployment → ongoing use**

The central question is not simply whether students can estimate a model. It is whether they can use analytics to **build something that another person or organisation can actually use**.

## Analytics as the vehicle for development

The subject should expose students to important forms of business analytics, potentially including prediction, experimentation and causal inference, forecasting, segmentation and other decision-oriented methods.

These methods should be taught intuitively and informally. Students should understand what question a method answers, when it is useful, what assumptions matter, how its performance should be evaluated and how its output informs a decision. Increasing statistical and econometric sophistication is deliberately not the objective.

Instead, **analytical problems provide the vehicle through which students develop increasingly sophisticated software-development capabilities**.

A predictive problem might require students to build a repeatable modelling pipeline rather than estimate a model once. An experimental problem might require automated ingestion and reporting of new results. A segmentation problem might culminate in an interactive tool through which managers explore customer groups and possible actions.

## From analysis to analytical product

Students should increasingly move beyond scripts and reports toward **analytical products**.

Shiny provides a natural environment for developing dashboards and interactive applications that place analytical capabilities in the hands of decision makers. Students confront practical questions about user requirements, inputs and outputs, validation, maintainability and what information a decision maker actually needs.

Projects reinforce professional development practices introduced elsewhere in the major: **Git and GitHub, modular software design, testing, documentation, project structure, dependency management and configuration**. Students should experience directly the distinction between code that produces the correct answer once and software that another person can reliably use.

**API development** can allow analytical functionality to be consumed by other applications rather than requiring every output to take the form of a dashboard or report. Containers and **Docker** provide a mechanism for packaging applications consistently for deployment.

Automation and scheduling allow analytical products to update as new information arrives. **Continuous integration and deployment** can connect GitHub-based development with automated testing and deployment. Logging, error handling and basic monitoring reinforce the principle that deployed analytics must continue to work when its developers are not watching it.

Cloud infrastructure provides an environment for deployment, storage and computation while reinforcing transferable architectural concepts rather than vendor-specific cloud administration.

## AI-assisted analytical development

AI should be incorporated into the development process rather than treated primarily as a standalone topic.

Students should learn to use **AI agents as collaborators in analytical development**: writing and refactoring code, constructing tests, diagnosing failures, navigating unfamiliar libraries, generating documentation and assisting with multi-step development workflows.

The educational objective is not simply greater productivity. Students must learn to specify tasks clearly, inspect what agents produce, test generated code and retain responsibility for whether the resulting analytical system is correct.

This makes AI part of **how contemporary analytical systems are built**, while reinforcing rather than replacing the need for sound development practices.

## Intended outcome

By the end of the subject, students should be capable of taking an important but incompletely specified business problem and developing a credible analytical solution from it.

The desired progression is from:

**“I can analyse data and estimate a model”**

to:

**“I can build, evaluate, deploy and maintain an analytical product that helps someone make a better business decision.”**

Together, the two second-year subjects establish a coherent progression:

**Data Engineering & Data Preparation:** *build the reliable data infrastructure.*

**Applied Analytics for Business Decision Making:** *build and operationalise the analytical solution.*

The result should be graduates who can take responsibility for a surprisingly large portion of the path from an important business problem to a reliable analytical product that people actually use.
