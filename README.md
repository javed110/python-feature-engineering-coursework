# Feature engineering and data preparation exercises

**Portfolio category: historical learning exercise.** This repository records foundations used in later health-data research. It is presented with its original scope and execution limits.

Category harmonization, derived Titanic features, missingness/imputation, outlier screens, DBSCAN, encoding, and wine-dataset scaling. Original repository documentation identifies this as Metropolia exploratory-data-analysis coursework.

Start with [Feature Engineering.ipynb](Feature%20Engineering.ipynb).

## Reproduction

Create a dedicated Python environment and install the notebook's libraries:

```bash
python -m venv .venv
python -m pip install numpy pandas matplotlib seaborn scikit-learn jupyterlab
python -m jupyter lab
```

Restore the exact original source files and expected columns when local datasets are required. Read the notebook before executing it. These setup commands are starting instructions, not a tested dependency lock or a claim that the historical notebook is currently runnable.

## Review status and limits

Most local teaching datasets are absent (Carvana-dataset-small-version.csv, Titanic.csv, Bankloan.txt and Iris.data). The outlier-mask cell contains a line-continuation SyntaxError. Some transformations depend on hard-coded row counts and include the target in imputation; do not reuse them as a validated predictive pipeline. The syntax defect is documented rather than concealing failed execution.

The October 2026 portfolio review inspected notebook code, syntax, stored errors and repository contents. It did not obtain missing datasets or independently re-execute every exercise. Original teaching provenance and source links remain authoritative for attribution and dataset rights.

For applied research, see the [dental AI survey](https://github.com/javed110/dental-ai-survey-pakistan) and [causal-method benchmark](https://github.com/javed110/parvovirus-b19-causal-ml-benchmark). Those projects document their methods, uncertainty and data-access boundaries separately.
