# Credit Risk Modeling

An end-to-end credit risk modeling project focused on predicting borrower default risk and developing a reproducible model validation workflow.

## Project Objectives

- Understand and validate the source dataset.
- Explore borrower and loan characteristics.
- Define the credit risk target and prediction horizon.
- Develop and validate predictive models.
- Evaluate discrimination and probability calibration.
- Explore scorecard development and model monitoring.

## Project Structure

```text
configs/       Project and model configuration
data/          Raw, intermediate, and processed data
notebooks/     Exploratory analysis and model development
src/           Reusable Python modules
scripts/       Data processing, training, and evaluation scripts
tests/         Automated tests
reports/       Generated figures and tables
docs/          Business, data, methodology, and validation documentation
presentations/ Presentation materials
```

## Getting Started

Create and activate a Python virtual environment, then install the dependencies:

```bash
python -m venv .venv
source .venv/Scripts/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
pip install -e .
```

The activation command above is intended for Git Bash on Windows. On macOS or Linux, use:

```bash
source .venv/bin/activate
```

## Data

Dataset details, access instructions, licensing, and the target definition will be documented as the project develops.

Raw datasets are excluded from version control by default. Do not commit confidential or personally identifiable information.

## Current Status

Initial repository structure created. Data sourcing, data validation, target definition, model development, and validation are planned project stages.

## License

See [LICENSE](LICENSE).