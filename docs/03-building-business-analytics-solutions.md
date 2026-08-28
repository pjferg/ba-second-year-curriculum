---
header-includes:
  - \usepackage{amssymb}
---

# CMCE20002 - Building Business Analytics Solutions {.unnumbered}

## Subject purpose

This subject develops students' ability to build and deploy a modest analytical decision tool for a defined business user. Students use accessible methods, evaluate whether the analysis is adequate, fit its results into the user's workflow, and operate the tool reliably as data and requirements change.

Together with CMCE20001 - Building Business Data Pipelines, the subject spans the path from raw data sources to a usable analytical product, but either subject may be taken first. This subject starts from prepared data, uses R and Shiny, and independently develops the practices needed to deliver a reliable decision tool.

## Subject coverage

### Define the decision

- Translate an incompletely specified business problem into a decision maker, a recurring decision, available actions and measures of success.
- Identify what information could improve the decision, the consequences of error, organisational constraints and how outputs should enter the existing workflow.
- Develop and refine solution requirements through simple prototypes and feedback from representative users.

### Develop adequate analysis

- Select an appropriately simple approach, describing and comparing outcomes using summaries, visualisations and differences in means while distinguishing statistical significance from business significance.
- Use regression and simple classification methods for prediction and adjusted description, evaluating performance on validation data against a credible baseline.
- Produce basic forecasts for recurring time-based decisions and evaluate them using temporal holdout data or backtesting.
- Use simple experiments and differences in means for causal questions, recognising how confounding and measurement error limit conclusions from observational data.
- Use clustering where stable, interpretable groups support different actions, and simulation where decisions must be compared under uncertainty.
- Examine uncertainty and sensitivity to reasonable changes in measurement, samples and assumptions, communicating how strongly the results support the decision.

### Build the decision tool

- Translate results into information, recommendations or decision rules, using visualisations and concise explanations to communicate uncertainty and limitations.
- Develop the tool principally as an interactive Shiny application, designing its inputs, outputs and interactions around the user's workflow.
- Test whether representative users can interpret and act on the output correctly, revising the analysis and interface in response.

### Deploy and maintain the solution

- Introduce and apply functions, modularity, testing, documentation, dependencies, configuration, Git and verified use of AI assistance within an R/Shiny project.
- Deploy the application through a supported managed pathway with automated checks before release.
- Automate necessary updates and implement basic error handling, logging and monitoring; manage credentials responsibly and define who responds when the tool fails or its performance deteriorates.

## Technical capabilities covered

|  |  |
|:--|:--|
| $\checkmark$ Programming and query languages | $\checkmark$ Version control and collaboration |
| $\checkmark$ Software design and coding practices | $\checkmark$ Testing and quality assurance |
| $\checkmark$ Documentation and reproducibility | $\checkmark$ Application development |
| $\checkmark$ Deployment and operations | $\checkmark$ Cloud infrastructure |
| $\checkmark$ Security fundamentals | $\checkmark$ AI-assisted development |

## Intended outcome

By the end of the subject, students should be able to deliver a deployed analytical tool that helps a defined business user make a recurring decision. They should be able to justify the analysis, demonstrate that the user can interpret and act on its output, and maintain the solution as data, performance and requirements change.
