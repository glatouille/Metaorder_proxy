# Generating realistic metaorders from public data

This repository contains a Jupyter Notebook that generates synthetic metaorders using public data.
It aims to provide an efficient tool for both practitioners and academics to overcome the scarcity and proprietary nature of metaorder datasets. It is based on the following paper: https://arxiv.org/abs/2503.18199 

## Abstract 

This paper introduces a novel algorithm for generating realistic metaorders from public trade data, addressing a longstanding challenge in price impact research that has traditionally relied on proprietary datasets. Our method effectively recovers all established stylized facts of metaorders impact, such as the Square Root Law, the concave profile during metaorder execution, and the post-execution decay. This algorithm not only overcomes the dependence on proprietary data, a major barrier to research reproducibility, but also enables the creation of larger and more robust datasets that may increase the quality of empirical studies. Our findings strongly suggest that average realized short-term price impact is not due to information revelation (as in the Kyle framework) but has a mechanical origin which could explain the universality of the Square Root Law.

## Disclamer 

- To simplify the notebook, we provide an example where synthetic metaorders are constructed on synthetic prices. As highlighted in the paper, the square-root law (SQL) cannot be recovered from naively generated synthetic prices. However, applying the same algorithm to real public trade data allows one to reproduce the results shown in the paper.
- We use here the simplest possible mapping function. Depending on the asset you choose—particularly its liquidity—it may be necessary to fine-tune the mapping function and its parameters for more accurate results.





