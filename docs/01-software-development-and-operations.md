# Building with Data: Integrating Software Development and Operations into the Business Analytics Major {.unnumbered}

The following is a useful test for the technical content of the Business Analytics major:

> Would an analyst embedded in finance, marketing, operations, consulting, public policy or another business function plausibly need this capability to turn an analysis into something reliable that colleagues can actually use?

This question makes clear that the major should be focused on developing students who can **build things with data that solve important business problems**. This requires more than the ability to analyse a prepared dataset or estimate a statistical model. Analysts increasingly need to acquire and organise data, write maintainable code, collaborate with others, connect analytical components, build tools for decision makers, and ensure that analytical processes operate reliably beyond a one-off analysis.

## Build what?

A script or notebook can demonstrate that an analysis worked once. But reliable analytical solutions must make it possible for the right analysis to work reliably again, for other people, with new data, in the setting where the decision is actually made.

Examples of such solutions include deployed pipelines that combine transaction, customer and external data; forecasts that update as new observations arrive and guide interventions; dashboards that monitor experiments or operations; simulations that compare staffing, inventory or pricing choices; and APIs that embed models in business systems.

## Core technical capabilities

To build analytics solutions, students need to progressively develop experience with:

- **Version control and collaboration:** Git and GitHub, including repositories, branching, pull requests and code review.
- **Software design and coding practices:** functions, modularity, sensible project and directory structures, naming conventions, consistent code and comment style, and reusable analytical components.
- **Testing and quality assurance:** unit tests, assertions, data validation and basic integration testing to ensure that analytical systems continue to work as inputs and requirements change.
- **Documentation and reproducibility:** READMEs, code documentation, dependency and environment management, and configuration.
- **Command line and scripting:** basic shell/Bash workflows, scripts and environment variables for executing and automating analytical tasks.
- **Data systems and integration:** databases, SQL, APIs, files and object storage, authentication and movement of data between systems.
- **Application development:** dashboards, interactive analytical tools using Shiny, and APIs that make analytical functionality available to other systems.
- **Deployment and operations:** containers and Docker, workflow scheduling and automation, basic continuous integration and deployment, error handling, logging and monitoring.
- **Cloud infrastructure:** practical exposure to cloud storage, computation, databases and deployment through a platform such as AWS or Azure.
- **Security fundamentals:** responsible management of credentials, API keys and secrets, permissions and basic authentication.
- **AI-assisted development:** agentic workflows supporting coding, testing, debugging, documentation and maintenance of analytical systems.

Our task is to decide on which of these we should cover in the second-year and third-year subjects. How ambitious do we want to be?

## Learning through building

These capabilities should generally **not be taught as a sequence of standalone technical topics**. Students should encounter them because increasingly serious business analytics problems create a need for them.

Students learn Git through collaboration, modularity as code becomes more complex, testing as pipelines confront new data, Docker when software must run elsewhere, scheduling when analyses must update, and logging when failures must be diagnosed.

## Modelling as a means rather than an end

Prediction, causal inference, forecasting, segmentation and other analytical methods provide important problems around which students learn to build complete analytical solutions. The emphasis shifts from deriving increasingly sophisticated models toward understanding the business problem, building out and tapping into the data pipeline, selecting and evaluating an appropriate analytical approach, and incorporating it into a reliable and usable analytical product.

The distinguishing practical capability of the major should be students' ability to move through the full analytics workflow:

**business problem → data → analysis → analytical product → deployment → ongoing use**
