# Classical Machine Learning from Scratch

A cleaned Python/Jupyter portfolio project implementing core classical machine learning algorithms from scratch, including regression, Bayesian inference, expectation maximization, Bayes classifiers, k-nearest neighbours, and neural networks.

| Algorithm | Category | What it demonstrates |
| --- | --- | --- |
| Ordinary Least Squares | Regression | Closed-form linear regression, polynomial feature construction, and mean squared error evaluation. |
| Ridge Regression | Regularized regression | L2 regularization, bias-variance tradeoffs, and validation against held-out synthetic data. |
| Expectation Maximization | Optimization / probabilistic modelling | Iterative parameter estimation under a latent-error formulation. |
| Full Bayesian Inference | Bayesian regression | Gaussian priors, posterior-style predictive estimates, and uncertainty visualization. |
| Bayes Classifiers | Probabilistic classification | Class-conditional density estimation, empirical priors, and cross-validation. |
| k-Nearest Neighbours | Instance-based classification | Distance computation, uniform voting, inverse-distance weighting, and model selection over `k`. |
| Multi-Layer Perceptron | Neural networks | A compact one-hidden-layer NumPy implementation with softmax output and gradient descent. |

## Relevance

This project demonstrates mathematical and practical foundations in classical machine learning, including linear models, regularization, probabilistic modelling, Bayesian reasoning, classification, nearest-neighbour methods, and neural networks. The notebook emphasizes transparent implementations and numerical experimentation rather than library-provided estimators.

## Academic and Portfolio Context

This is a cleaned portfolio version of MSc-level implementation practice. It is intended to show from-scratch implementation ability, applied mathematics, and classical machine learning fundamentals. It is not presented as peer-reviewed research or production software.

## How to Run

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

On Windows, activate the environment with:

```powershell
.venv\Scripts\activate
```

Then open `ml_classic_scratch.ipynb` in Jupyter.

## Repository Contents

| File | Description |
| --- | --- |
| `ml_classic_scratch.ipynb` | Main notebook containing from-scratch implementations and experiments. |
| `requirements.txt` | Python dependencies needed to run the notebook. |
| `CLEANUP_REPORT.md` | Notes on what was inspected, changed, executed, and flagged for review. |
| `LICENSE_OR_NOTICE.md` | Cautious portfolio and third-party material notice. |
