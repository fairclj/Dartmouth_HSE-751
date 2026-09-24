# Reproducibility Exercise: Diabetes Risk Factor Analysis

## Professional Scenario
You are a data scientist at a teaching hospital within a multi-site academic health system. Your team has developed a preliminary analytical notebook using a diabetes dataset. The notebook was originally created for internal exploratory analysis and now needs to be prepared for use by the data science team at another clinical site within the health system.

The receiving team should be able to obtain the project files, understand the analytical workflow, execute the notebook in its own computational environment, and reproduce the intended results without additional guidance from you.

## Purpose
This exercise develops your ability to create transparent, organized, reproducible computational workflows in health data science. You will improve an existing analysis so that another data science team can execute the same workflow and obtain consistent results.

## Your Task
Begin by reviewing and executing the provided starter notebook. Modify and reorganize it so that it can be independently reproduced by the receiving clinical site's data science team.

Address every embedded **DATA SCIENCE DIRECTOR NOTE**, but do not assume that those notes identify every problem. You are also responsible for identifying and resolving additional reproducibility, documentation, organization, and execution issues.

## Required Notebook Structure
Organize the final notebook using a clear structure that includes:

1. Title
2. Purpose and overview
3. Setup/environment
4. Data source/provenance
5. Data loading
6. Data validation
7. Data preparation
8. Analysis
9. Results
10. Conclusions

## Requirements

### 1. Workflow Reproducibility
- Ensure the notebook executes successfully from beginning to end.
- Verify consistent results from a clean runtime using **Restart session and run all** (or the equivalent in your environment).
- Identify and resolve issues that prevent reproducibility.
- Control randomness where needed.

### 2. Dependency and Environment Management
- Identify required libraries and dependencies.
- Document package versions and installation commands where appropriate.
- Verify compatibility in the environment used for the project.
- Include a reproducible setup/environment section near the beginning of the notebook.

### 3. Notebook Documentation and Independent Usability
Use Markdown throughout the notebook to provide sufficient instructions and context for another data science team to execute the workflow independently.

Your Markdown should, where appropriate:
- Explain the purpose of each major workflow section.
- Provide instructions for actions the user must complete.
- Explain how the dataset should be imported or accessed.
- Describe important analytical and preprocessing decisions.
- Explain key outputs and how they should be interpreted.
- Identify assumptions, requirements, and limitations.

Inline code comments should explain code where useful, while Markdown should explain the broader analytical workflow to another human reader.

### 4. Data and Output Verification
- Confirm successful dataset loading and preprocessing.
- Add appropriate validation checks.
- Ensure tables, figures, mathematical notation, and analytical outputs render correctly.
- Verify that intended outputs are consistent across executions.

### 5. Data Science Director Requests
Address all review notes embedded in the starter notebook. These include requests related to:
- Mathematical notation and dataset-specific statistical explanations.
- Two additional bivariate visualizations.
- A correlation matrix and interpretation.
- One additional appropriate inferential statistical method, including mathematical notation, description, result, and dataset-specific interpretation.
- Customization of the correctly rendered statistical/machine-learning notation so that generic placeholders accurately represent the diabetes dataset.
- Reproducibility, dependencies, data loading, data provenance, validation, workflow organization, and independent usability.

### 6. README
Create a clear README that includes:
- Project title and purpose.
- Brief description of the analysis.
- Dataset source/provenance.
- Required software and libraries.
- Package versions where relevant.
- Setup/installation instructions.
- Instructions for executing the notebook from start to finish.
- Expected outputs.
- Dataset requirements.
- Assumptions and limitations.
- Computational environment information.

### 7. GitHub Repository
Complete the exercise in Google Colab and include a link to the completed Colab notebook in your GitHub repository.

Your repository should include:
- A link to the completed Google Colab notebook.
- A downloaded copy of the completed `.ipynb` notebook.
- The project dataset, or clear instructions for obtaining it if redistribution is not permitted.
- A README file for this exercise.
- Any supporting files needed to reproduce the analysis.

Before submitting, verify that the Google Colab link is accessible and that the .ipynb file in the repository reflects the final version of your completed notebook.

### 8. Reproducibility Summary
Submit a **150–250 word Reproducibility Summary** describing:
- Major reproducibility issues you identified.
- Changes you made.
- How you verified that the final workflow is reproducible.

## Evaluation Criteria

### Reproducibility and Execution — 40%
- Notebook executes successfully from start to finish.
- Reproducible results following Restart session and run all.
- Appropriate management of software dependencies.

### Documentation and Workflow Organization — 30%
- Clear and informative README.
- Logical notebook organization.
- Effective Markdown instructions, inline comments, and modular functions where appropriate.
- Sufficient guidance for independent execution by the receiving data science team.

### Technical Accuracy — 20%
- Correct data loading, preprocessing, and analytical steps.
- Proper rendering of outputs, visualizations, and mathematical notation.
- Accurate dependency identification.
- Appropriate completion of the requested analytical additions.

### Submission Quality — 10%
- Complete repository contents.
- Functional GitHub repository.
- Professional organization and presentation.

## Success Criterion
A data scientist at another clinical site should be able to obtain your repository, follow the README and notebook Markdown instructions, execute the complete workflow in a clean environment, and reproduce the intended analysis without contacting you for additional guidance.
