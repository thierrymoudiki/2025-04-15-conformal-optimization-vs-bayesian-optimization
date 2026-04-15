# Benchmark: ConfBO vs 17 optimizers on 72 datasets

This notebook compares conformal optimization to bayesian optimization on 72 data sets ([OpenML-CC18 subsampled](https://github.com/thierrymoudiki/openml-cc18-reduced))

**Key finding**: 

ConfBO, conformal optimization variants achieve similar balanced accuracy (~0.76) with no statistical differences among top 12 methods. GP_BO and RandomSearch significantly underperform when compared to conformal optimization.

**File**:

ipynb file with full statistical analysis (Friedman test, pairwise Wilcoxon, ranking tables)
