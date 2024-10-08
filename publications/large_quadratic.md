---
author: <b>Tong Chen</b>, Thomas Lumley
date: 2019-11-01
title: "Numerical evaluation of methods approximating the distribution of a large quadratic form in normal variables"
details: <em>Computational Statistics & Data Analysis</em>, 139, 75-81
doi: 10.1016/j.csda.2019.05.002
categories: Methodology
---

Quadratic forms of Gaussian variables occur in a wide range of applications in statistics. They can be expressed as a linear combination of chi-squareds. The coefficients in the linear combination are the eigenvalues $\lambda_{1},...,\lambda_n$ of $\Sigma A$, where $A$ is the matrix representing the quadratic form and $\Sigma$ is the covariance matrix of the Gaussians. The previous literature mostly deals with approximations for small quadratic forms $(n<10)$ and moderate p-values $(p>10^{-2})$. Motivated by genetic applications, moderate to large quadratic forms ($300<n<12,000$) and small to very small p-values $(p<10^{-4})$ are studied. Existing methods are compared under these settings and a leading-eigenvalue approximation, which only takes the largest $k$ eigenvalues, is shown to have the computational advantage without any important loss in accuracy. For time complexity, a leading-eigenvalue approximation reduces the computational complexity from $O(n^3)$ to $O(n^2k)$ on extracting eigenvalues and avoids speed problems with computing the sum of $n$ terms. For accuracy, the existing methods have some limits on calculating small p-values under large quadratic forms. Moment methods are inaccurate for very small p-values, and Farebrother's method is not usable if the minimum eigenvalue is much smaller than others. Davies's method is usable for p-values down to machine epsilon. The saddlepoint approximation is proved to have bounded relative error for any $A$ and $\Sigma$ in the extreme right tail, so it is usable for arbitrarily small p-values.
