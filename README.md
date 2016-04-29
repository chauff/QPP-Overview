# QPP-Overview
This page provides an overview of pre/post-retrieval QPP results on common corpora, 
retrieval models and evaluation metrics. The page is ordered by corpus. 

## WT10g

Reference | Queries | Retrieval model | Predictor | Linear correlation coefficient | Spearman's Rho | Kendall's Tau
--- | --- | --- | --- | --- | --- | ---
`[2]` | 451-500 | Language model (Dirichlet smoothing) | MaxIDF | 0.090| 0.302 |  0.227
`[2]` | 451-500 | Language model (Dirichlet smoothing) | MaxSCQ | 0.447| 0.624 |  0.456
`[2]` | 451-500 | Language model (Dirichlet smoothing) | MaxVAR | 0.354| 0.529 |  0.358
`[2]` | 501-550 | Language model (Dirichlet smoothing) | MaxIDF | 0.507| 0.408 |  0.291
`[2]` | 501-550 | Language model (Dirichlet smoothing) | MaxSCQ | 0.418| 0.378 |  0.274
`[2]` | 501-550 | Language model (Dirichlet smoothing) | MaxVAR | 0.538| 0.502 |  0.372
`[3]` | 451-550 | BM25 | NCQ | | 0.342 |
`[3]` | 451-550 | BM25 | Query Clarity | | 0.358 |
`[3]` | 451-550 | BM25 | Sigma-50% | | 0.447 |


## GOV2

Reference | Queries | Retrieval model | Predictor | Linear correlation coefficient | Spearman's Rho | Kendall's Tau
--- | --- | --- | --- | --- | --- | ---
`[1]` | 701-800 | Markov random field | Query Clarity | 0.333 | |
`[1]` | 701-800 | Markov random field | Query Feedback | 0.480 | |
`[1]` | 701-800 | Markov random field | Weighted Information Gain | 0.574 | |
`[1]` | 701-800 | Markov random field | Robustness | 0.317 | |
`[2]` | 701-850 | Language model (Dirichlet smoothing) | MaxIDF | 0.297| 0.326 |  0.219
`[2]` | 701-850 | Language model (Dirichlet smoothing) | MaxSCQ | 0.357| 0.347 |  0.231
`[2]` | 701-850 | Language model (Dirichlet smoothing) | MaxVAR | 0.359| 0.369 |  0.247


## ClueWeb09


## Bibliography

[1] Zhou, Yun, and W. Bruce Croft. "Query performance prediction in web search environments." Proceedings of the 30th annual international ACM SIGIR conference on Research and development in information retrieval. ACM, 2007.

[2] Zhao, Ying, Falk Scholer, and Yohannes Tsegay. "Effective pre-retrieval query performance prediction using similarity and variability evidence." Advances in Information Retrieval. Springer Berlin Heidelberg, 2008. 52-64.

[3] Cummins, Ronan, Joemon Jose, and Colm O'Riordan. "Improved query performance prediction using standard deviation." Proceedings of the 34th international ACM SIGIR conference on Research and development in Information Retrieval. ACM, 2011.

