# STA_Assignments

### Course assignments for STA1 — Statistics and Data Analysis for Engineers

This repository contains our group assignments for **STA1 — Statistics and Data Analysis for Engineers**.

The assignments cover topics such as descriptive statistics, probability, random variables, probability distributions, data analysis, and visualisation. The work is completed in English using Jupyter notebooks and Python.

The purpose of this repository is to keep our notebooks, datasets, code, visualisations, interpretations, and supporting documentation organised in one place throughout the course.

## Group members

| Name            | Student number |
| --------------- | -------------: |
| Bibek Chaudhary |         344326 |
| Samo Susa       |         343876 |
| Sneha Koirala   |         345788 |
| Tomas Psotka    |         343207 |

## Assignments

| Assignment                                      | Topic                                      | Main contents                                                                                                                                                                                 | Status      |
| ----------------------------------------------- | ------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| [Assignment 1](./Assignment1/Assignment1.ipynb) | Data and Probability Foundations           | Descriptive statistics, data visualisation, probability rules, conditional probability, Bayes' theorem, AI-use statement, and overall conclusion                                              | Completed   |
| [Assignment 2](./Assignment2/Assignment2.ipynb) | Discrete and Continuous Probability Models | Finite random variables, PMF and CDF, binomial and Poisson models, uniform and normal distributions, exponential models, graphical model assessment, AI-use statement, and overall conclusion | In progress |
| Future assignments                              | To be added                                | New notebooks and supporting files will be listed here as the course continues                                                                                                                | Not started |

## Repository structure

Each assignment is stored in its own folder, while shared datasets are kept in the repository-level `data/` directory.

A typical structure is:

    STA_Assignments/
    │
    ├── Assignment1/
    │   └── Assignment1.ipynb
    │
    ├── Assignment2/
    │   └── Assignment2.ipynb
    ├── data/
    │
    └── README.md

Original datasets should remain unchanged. Any cleaning, transformation, calculation, or filtering should be performed inside the relevant notebook.

## Requirements

The notebooks use **Python 3** together with the following main packages:

* Jupyter Notebook or JupyterLab
* NumPy
* pandas
* Matplotlib
* SciPy

The required packages can be installed with:

```bash
python -m pip install jupyter numpy pandas matplotlib scipy
```

## Working with the notebooks

For each assignment task, we generally follow this structure:

1. State or introduce the question, random variable, event, or statistical problem.
2. Explain the relevant assumptions, definitions, or formulas in Markdown where required.
3. Use an executable Python cell to perform the calculation or visualisation.
4. Display the resulting values, table, or plot.
5. Follow the output with a short interpretation.
6. Relate the interpretation directly to the assignment question and engineering context.

The aim is not only to obtain the correct numerical result, but also to explain what the result means and understand the statistical model behind it.

## Before submission

Before submitting an assignment, the group should confirm that:

* all required datasets load correctly from the local `data` folder;
* all notebook cells execute successfully from top to bottom;
* all required random variables, events, supports, and parameters are clearly defined;
* formulas and Python calculations are consistent with each other;
* probability functions such as PMF, PDF, CDF, SF, and PPF are used appropriately;
* SciPy distributions use the correct parameterisation;
* tables and plots have clear titles, labels, units, and legends where appropriate;
* every important output is followed by an interpretation;
* model assumptions and limitations are discussed where required;
* empirical results and model-based probabilities are clearly distinguished;
* sample standard deviations use \(n-1\) where required;
* potential unusual observations are investigated rather than automatically removed;
* numerical results agree with the written conclusions;
* AI use is disclosed honestly; and
* every group member understands and can explain the submitted work.

## Group collaboration

To reduce merge conflicts and keep the repository organised:

* Pull the latest version before beginning work.
* Avoid editing the same Jupyter notebook simultaneously when possible.
* Work on separate assignment sections or coordinate changes before editing.
* Use clear commit messages describing what was added or changed.
* Review one another's calculations, code, plots, and interpretations before submission.
* Keep the original datasets unchanged.
* Perform data processing inside the notebooks.
* Do not include unnecessary personal information in the repository.

Example commit messages:

```text
Complete Assignment 2 Part 1
Add binomial and Poisson calculations
Fix probability interpretations
Update Assignment 2 plots
Review notebook before submission
```

## Use of AI

AI tools may be used when permitted by the assignment instructions.

They may assist with:

* explaining statistical concepts;
* translating probability statements into Python or SciPy functions;
* checking formulas and parameterisations;
* drafting or debugging Python code;
* reviewing calculations;
* improving plots;
* checking assumptions;
* improving written explanations and clarity.

AI-generated material should not be accepted automatically. All code, calculations, interpretations, and explanations must be reviewed and understood by the group before submission.

When required by an assignment, the notebook should clearly state:

* which AI tool or tools were used;
* what the AI contributed;
* what was changed, corrected, or rejected by the group; and
* how the final results were verified.

The group remains responsible for everything included in the submitted work.

## Academic responsibility

This repository contains collaborative academic work completed as part of the STA1 course at VIA University College.

All submitted material should follow the assignment instructions and VIA University College's academic-integrity requirements. Calculations, interpretations, code, visualisations, and sources should be checked before submission.

Using AI or other supporting tools does not replace the requirement to understand the submitted work. Every group member should be prepared to explain the statistical concepts, models, assumptions, calculations, and Python code used in the assignments.
