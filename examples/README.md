
# Example

This directory contains example scripts demonstrating ATHENA's functionality.

## Feature Map Bayesian Optimization Example

`feature_map_bayes_opt_example.py` demonstrates the use of the
`bayesian-optimization` package for tuning feature map parameters in ATHENA's
Kernel Active Subspaces.

This example:

- Sets up a feature map with a Laplace distribution
- Tunes the hyperparameters of the feature map using Bayesian Optimization
- Fits a KAS model and transforms inputs to the active subspace

To run the example:

```bash
python feature_map_bayes_opt_example.py
```

This shows how the `'bso'` method in `tune_pr_matrix` now uses the `bayesian-optimization`
package as a replacement for the previous GPyOpt dependency.
