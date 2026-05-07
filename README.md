# FRDPCA
Here provides the codes to reproduce the numerical experiments in the paper "Few-Round Distributed Principal Component Analysis: Closing the Statistical Efficiency Gap". 

The benchmark datasets and the corresponding details could be found at https://huggingface.co/datasets/inria-soda/tabular-benchmark.

## Summary

Under weaker local signal-to-noise ratios, we improve upon the celebrated one-round distributed principal component analysis (PCA) algorithm (Fan et al., 2019), which is designed in the spirit of divide-and-conquer by introducing a few additional communication rounds of consensus. The proposed shifted subspace iteration algorithm is able to close the local phase transition gap, reduce the asymptotic variance, and alleviate potential bias. Our estimation procedure is easy to implement and tuning-free. The resulting estimator is shown to be statistically efficient after an acceptable number of iterations.

## Citation

```
@article{li2025few,
  title={Few-Round Distributed Principal Component Analysis: Closing the Statistical Efficiency Gap by Consensus},
  author={Li, ZeYu and Zhang, Xinsheng and Zhou, Wang},
  journal={arXiv preprint arXiv:2503.03123},
  year={2025}
}
```
