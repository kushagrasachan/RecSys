A recommender system using Matrix Factorisation for collaborative filtering on explicit and implicit rating data.

[MF_Recommender_nb.ipynb](https://github.com/kushagrasachan/RecSys/blob/main/MF_Recommender_nb.ipynb) contains a Python class implementation for Matrix Factorisation, exposing methods able to learn latent factors from implicit or explicit user-feedback data.

Refer to Yifan Hu et al. (present as [cf.pdf](https://github.com/kushagrasachan/RecSys/blob/main/cf.pdf)) and Takács et al. ([Conjugate Gradient Method for Implicit Collaborative Filtering.pdf](https://github.com/kushagrasachan/RecSys/blob/main/Conjugate%20Gradient%20Method%20for%20Implicit%20Collaborative%20Filtering.pdf)) for more information.

The training methods are optimised for data sparsity using clever manipulation of scipy sparse matrices and other optimisations.
