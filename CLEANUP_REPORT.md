# Cleanup Report

## 1. Files Inspected

* `README.md`
* `ml_classic_scratch.ipynb`

## 2. Files Changed

* `README.md`
* `ml_classic_scratch.ipynb`
* `requirements.txt`
* `.gitignore`
* `LICENSE_OR_NOTICE.md`
* `CLEANUP_REPORT.md`

## 3. Algorithms Documented

* Ordinary Least Squares
* Ridge Regression
* Expectation Maximization
* Full Bayesian Inference
* Bayes Classifiers
* k-Nearest Neighbours
* Multi-Layer Perceptron

## 4. Notebook Execution Status

The notebook was executed top to bottom locally with:

```bash
python -m jupyter nbconvert --to notebook --execute --inplace ml_classic_scratch.ipynb --ExecutePreprocessor.timeout=300
```

Execution completed successfully on June 22, 2026. All 55 code cells executed, no code-cell error outputs were present, and notebook validation passed after updating the notebook metadata to `nbformat_minor: 5`.

## 5. Broken Cells or Missing Dependencies

No broken cells or missing dependencies were found during the executed run.

The execution emitted environment warnings related to Windows/IPython profile permissions and an old notebook-format metadata warning before the metadata update. These warnings did not stop notebook execution or create code-cell errors.

## 6. Sections Removed or Rewritten for Academic-Integrity Reasons

* Removed the original author/course header from the notebook.
* Rewrote public-facing text that framed the work as raw coursework or step-by-step answers.
* Removed 12 embedded image-only cells that appeared to contain course prompt text.
* Replaced external Google Drive dataset links with bundled scikit-learn datasets so the notebook is self-contained.
* Replaced the README license claim with a cautious notice file because the original material may include course-derived context.

## 7. Manual Review Items Before Public Upload

* Confirm that the cleaned notebook no longer contains material that should remain private.
* Review generated plots and numerical outputs for presentation quality.
* Decide whether to add a formal open-source license only after confirming rights for all notebook content.
* Review the cautious notice in `LICENSE_OR_NOTICE.md` before publishing.
* Consider whether to keep the notebook as a single portfolio artifact or later split reusable code into modules.
