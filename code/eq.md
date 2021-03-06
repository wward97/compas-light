### Equalized Odds

The last fairness metric we consider is based on the difference in *error rates* between groups. Hardt et al. [5](#References) propose to look at the difference in the true positive and false positive rates for each group. This aligns with the analysis performed by Propublica. WE can examine these values looking at is the ROC for each group. We normalize the score between 0 and 1. The ROC thresholds produced by `scikitlearn` are the same.

`%load code/eq`

Discuss these results and copmare how these metrics show that there is (or is not) a disparity.  Then you're done! Leave your breakout room.

For an extra activity if you finish early, consider CORELS with `mdshow('code/corels.md')`
