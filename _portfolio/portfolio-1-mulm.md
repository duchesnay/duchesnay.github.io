---
title: "Univariate statistics & Residualization"
collection: portfolio
---

[MULM](https://github.com/neurospin/pylearn-mulm/) provide basic features similar to "statmodels" (like OLS) where Y is a matrix of many responses where many independant fit are requested. Usefull to perform **univariate statistics** and **residualization** to remove site, or age effect. MULM provides a [`Residualizer` module](https://neurospin.github.io/pylearn-mulm/auto_gallery/plot_residualizer.html#sphx-glr-auto-gallery-plot-residualizer-py) that can be used, as scalers, in [scikit-learn pipelines](https://neurospin.github.io/pylearn-mulm/auto_gallery/plot_residualization_as_sklearn_preprocessing.html#sphx-glr-auto-gallery-plot-residualization-as-sklearn-preprocessing-py).


# Univariate statistics

[Univariate T and F tests](https://neurospin.github.io/pylearn-mulm/auto_gallery/plot_univariate_t_and_f_tests.html#sphx-glr-auto-gallery-plot-univariate-t-and-f-tests-py). Usefull in neuroimaging to perform Voxel Based Morphometry (VBM) in python.

# Residualizer

[Residualizer](https://neurospin.github.io/pylearn-mulm/auto_gallery/plot_residualizer.html#sphx-glr-auto-gallery-plot-residualizer-py) basic usage.

[Residualization in scikit-learn](https://neurospin.github.io/pylearn-mulm/auto_gallery/plot_residualization_as_sklearn_preprocessing.html#sphx-glr-auto-gallery-plot-residualization-as-sklearn-preprocessing-py) pipelines.

# Example in neuroimaging

[Univariate statistics (Voxel Based Morphometry) & Residualization (remove sex) before age prediction with scikit-learn](https://neurospin.github.io/pylearn-mulm/auto_gallery/plot_brain_age_sex_statistics_residualization.html#sphx-glr-auto-gallery-plot-brain-age-sex-statistics-residualization-py)
