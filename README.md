# QPP-Overview
This page provides an overview of pre/post-retrieval QPP results on common corpora, 
retrieval models and evaluation metrics. The page is ordered by corpus. It is not claimed to be complete.


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
`[4]` | 451-550 | Language model (Dirichlet smoothing) | Clarity | 0.348| |
`[4]` | 451-550 | Language model (Dirichlet smoothing) | UEF(Clarity) | 0.483| |
`[4]` | 451-550 | Language model (Dirichlet smoothing) | WIG | 0.376| |
`[4]` | 451-550 | Language model (Dirichlet smoothing) | UEF(WIG) | 0.453| |
`[4]` | 451-550 | Language model (Dirichlet smoothing) | NQC | 0.488| |
`[4]` | 451-550 | Language model (Dirichlet smoothing) | UEF(NQC) | 0.522| |
`[4]` | 451-550 | Language model (Dirichlet smoothing) | QF | 0.426| |
`[4]` | 451-550 | Language model (Dirichlet smoothing) | UEF(QF) | 0.526| |
`[5]` | 451-550 | Language model (Dirichlet smoothing) | Clarity | 0.432| |
`[5]` | 451-550 | Language model (Dirichlet smoothing) | Clarity+MaxVARTF.IDF | 0.450| |
`[5]` | 451-550 | Language model (Dirichlet smoothing) | QF | 0.483| |
`[5]` | 451-550 | Language model (Dirichlet smoothing) | QF+MaxVARTF.IDF | 0.496| |
`[5]` | 451-550 | Language model (Dirichlet smoothing) | WIG | 0.376| |
`[5]` | 451-550 | Language model (Dirichlet smoothing) | WIG+MaxVARTF.IDF | 0.431| |
`[7]` | 451-550 | Language model (Dirichlet smoothing) | Delta(QR1)/Delta(QG) | | |0.260
`[9]` | 451-550 | Language model (Dirichlet smoothing) | MaxIDF | 0.300 | |0.280
`[9]` | 451-550 | Language model (Dirichlet smoothing) | Simplified Clarity | 0.130 | |0.170
`[9]` | 451-550 | Language model (Dirichlet smoothing) | MaxSCQ | 0.410 | |0.340
`[9]` | 451-550 | Language model (Dirichlet smoothing) | MaxVAR | 0.420 | |0.330
`[10]` | 451-550 | Language model (Dirichlet smoothing) | MaxVAR | 0.406 | |
`[10]` | 451-550 | Language model (Dirichlet smoothing) | NQC | 0.405 | |
`[10]` | 451-550 | Language model (Dirichlet smoothing) | UEF(NQC) | 0.435 | |
`[10]` | 451-550 | Language model (Dirichlet smoothing) | UEF(Improved Clarity) | 0.563 | |
`[10]` | 451-550 | Language model (Dirichlet smoothing) | LTRoq | 0.346 | |


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
`[4]` | 701-850 | Language model (Dirichlet smoothing) | Clarity | 0.433| |
`[4]` | 701-850 | Language model (Dirichlet smoothing) | UEF(Clarity) | 0.462| |
`[4]` | 701-850 | Language model (Dirichlet smoothing) | WIG | 0.479| |
`[4]` | 701-850 | Language model (Dirichlet smoothing) | UEF(WIG) | 0.458| |
`[4]` | 701-850 | Language model (Dirichlet smoothing) | NQC | 0.360| |
`[4]` | 701-850 | Language model (Dirichlet smoothing) | UEF(NQC) | 0.393| |
`[4]` | 701-850 | Language model (Dirichlet smoothing) | QF | 0.476| |
`[4]` | 701-850 | Language model (Dirichlet smoothing) | UEF(QF) | 0.491| |
`[5]` | 701-850 | Language model (Dirichlet smoothing) | Clarity | 0.456| |
`[5]` | 701-850 | Language model (Dirichlet smoothing) | Clarity+MaxVARTF.IDF | 0.447| |
`[5]` | 701-850 | Language model (Dirichlet smoothing) | QF | 0.566| |
`[5]` | 701-850 | Language model (Dirichlet smoothing) | QF+MaxVARTF.IDF | 0.574| |
`[5]` | 701-850 | Language model (Dirichlet smoothing) | WIG | 0.486| |
`[5]` | 701-850 | Language model (Dirichlet smoothing) | WIG+MaxVARTF.IDF | 0.465| |
`[6]` | 701-750 | Language model | Query Clarity | | |0.139
`[6]` | 751-800 | Language model  | Query Clarity | | |0.171
`[6]` | 701-750 | Language model  | Robustness | | |0.150
`[6]` | 751-800 | Language model  | Robustness | | |0.208
`[6]` | 701-750 | Language model  | Autocorrelation | | |0.454
`[6]` | 751-800 | Language model  | Autocorrelation | | |0.383
`[7]` | 701-850 | Language model (Dirichlet smoothing) | Delta(R2G)/Delta(R1G) | | |0.204
`[8]` | 701-750 | Language model (Dirichlet smoothing) | Query Clarity | 0.305 | |0.134
`[8]` | 701-750 | Language model (Dirichlet smoothing) | Robustness | 0.341 | |0.213
`[8]` | 701-750 | Language model (Dirichlet smoothing) | Query Clarity+Robustness | 0.374 | |0.226
`[8]` | 701-750 | Language model (Dirichlet smoothing) | Query Clarity | 0.206 | |0.171
`[8]` | 701-750 | Language model (Dirichlet smoothing) | Robustness | 0.301 | |0.208
`[8]` | 701-750 | Language model (Dirichlet smoothing) | Query Clarity+Robustness | 0.362 | |0.252
`[9]` | 701-850 | Language model (Dirichlet smoothing) | MaxIDF | 0.350 | |0.250
`[9]` | 701-850 | Language model (Dirichlet smoothing) | Simplified Clarity | 0.260 | |0.200
`[9]` | 701-850 | Language model (Dirichlet smoothing) | MaxSCQ | 0.420 | |0.280
`[9]` | 701-850 | Language model (Dirichlet smoothing) | MaxVAR | 0.430 | |0.290
`[10]` | 451-550 | Language model (Dirichlet smoothing) | MaxVAR | 0.384 | |
`[10]` | 451-550 | Language model (Dirichlet smoothing) | NQC | 0.336 | |
`[10]` | 451-550 | Language model (Dirichlet smoothing) | UEF(NQC) | 0.417 | |
`[10]` | 451-550 | Language model (Dirichlet smoothing) | UEF(Improved Clarity) | 0.537 | |
`[10]` | 451-550 | Language model (Dirichlet smoothing) | LTRoq | 0.570 | |


## ClueWeb09

Reference | Queries | Retrieval model | Predictor | Linear correlation coefficient | Spearman's Rho | Kendall's Tau
--- | --- | --- | --- | --- | --- | ---
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | Clarity | 0.105| |
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | Clarity+MaxVARTF.IDF | 0.555| |
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | Clarity+e-dispersion | 0.353| |
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | QF | 0.516| |
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | QF+MaxVARTF.IDF | 0.651| |
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | QF+e-dispersion | 0.569| |
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | WIG | 0.507| |
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | WIG+MaxVARTF.IDF | 0.587| |
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | WIG+e-dispersion | 0.525| |
`[5]` |  51-100 (cat B) | Language model (Dirichlet smoothing) | Clarity | -0.147| |
`[5]` |  51-100 (cat B) | Language model (Dirichlet smoothing) | Clarity+MaxVARTF.IDF | 0.206| |
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | Clarity+e-dispersion | 0.095| |
`[5]` |  51-100 (cat B) | Language model (Dirichlet smoothing) | QF | 0.393| |
`[5]` |  51-100 (cat B) | Language model (Dirichlet smoothing) | QF+MaxVARTF.IDF | 0.557| |
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | QF+e-dispersion | 0.495| |
`[5]` |  51-100 (cat B) | Language model (Dirichlet smoothing) | WIG | 0.415| |
`[5]` |  51-100 (cat B) | Language model (Dirichlet smoothing) | WIG+MaxVARTF.IDF | 0.333| |
`[5]` |  1-50 (cat B) | Language model (Dirichlet smoothing) | WIG+e-dispersion | 0.471| |
`[10]` | 1-200 (cat B) | Language model (Dirichlet smoothing) | MaxVAR | 0.358 | |
`[10]` | 1-200 (cat B) | Language model (Dirichlet smoothing) | NQC | 0.234 | |
`[10]` | 1-200 (cat B) | Language model (Dirichlet smoothing) | UEF(NQC) | 0.272 | |
`[10]` | 1-200 (cat B) | Language model (Dirichlet smoothing) | UEF(Improved Clarity) | 0.265 | |
`[10]` | 1-200 (cat B) | Language model (Dirichlet smoothing) | LTRoq | 0.512 | |



## Bibliography

[1] Zhou, Yun, and W. Bruce Croft. "Query performance prediction in web search environments." Proceedings of the 30th annual international ACM SIGIR conference on Research and development in information retrieval. ACM, 2007.

[2] Zhao, Ying, Falk Scholer, and Yohannes Tsegay. "Effective pre-retrieval query performance prediction using similarity and variability evidence." Advances in Information Retrieval. Springer Berlin Heidelberg, 2008. 52-64.

[3] Cummins, Ronan, Joemon Jose, and Colm O'Riordan. "Improved query performance prediction using standard deviation." Proceedings of the 34th international ACM SIGIR conference on Research and development in Information Retrieval. ACM, 2011.

[4] Shtok, Anna, Oren Kurland, and David Carmel. "Using statistical decision theory and relevance models for query-performance prediction." Proceedings of the 33rd international ACM SIGIR conference on Research and development in information retrieval. ACM, 2010.

[5] Kurland, Oren, et al. "Back to the roots: A probabilistic framework for query-performance prediction." Proceedings of the 21st ACM international conference on Information and knowledge management. ACM, 2012.

[6] Diaz, Fernando. "Performance prediction using spatial autocorrelation." Proceedings of the 30th annual international ACM SIGIR conference on Research and development in information retrieval. ACM, 2007.

[7] Collins-Thompson, Kevyn, and Paul N. Bennett. "Predicting query performance via classification." Advances in Information Retrieval. Springer Berlin Heidelberg, 2010. 140-152.

[8] Zhou, Yun, and W. Bruce Croft. "Measuring ranked list robustness for query performance prediction." Knowledge and Information Systems 16.2 (2008): 155-171.

[9] Hauff, Claudia, Djoerd Hiemstra, and Franciska de Jong. "A survey of pre-retrieval query performance predictors." Proceedings of the 17th ACM conference on Information and knowledge management. ACM, 2008.

[10] Raiber, Fiana, and Oren Kurland. "Query-performance prediction: Setting the expectations straight." Proceedings of the 37th international ACM SIGIR conference on Research & development in information retrieval. ACM, 2014.
