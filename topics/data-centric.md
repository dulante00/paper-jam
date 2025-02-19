
## Data-centric AI/Machine Learning

This repo is used to hold papers that propose data-centric perspectives for machine learning, for examples:
- [Understanding data augmentation](#understanding-data-augmentation)
- [Data curation](#data-curation) (data cleaning, deduplication)
- [Dataset distillation](#dataset-distillation) (data summarization, coreset, prototype)
- Fast cross-validation (Jackknife)
- Datapoint(s) attribution and valuation
- Datapoint(s) removal and machine unlearning

🤍 ***Unclassified papers***

- [Beyond neural scaling laws: beating power law scaling via data pruning](https://openreview.net/pdf?id=UmvSlP-PyV), `nips2022` `data selection`.
- [Repairing Neural Networks by Leaving the Right Past Behind](https://rt416.github.io/pdf/modelrepairment_preprint_2022.pdf), `nips2022`.`data deletion` `model edit` `failure mode` `causal inference`.

### Understanding data augmentation

- [Explaining the Efficacy of Counterfactually Augmented Data](https://arxiv.org/abs/2010.02114), `iclr2021`.
  - Also from the same author [Learning the Difference that Makes a Difference with Counterfactually-Augmented Data](https://arxiv.org/abs/1909.12434).
- [How Much Data Are Augmentations Worth? An Investigation into Scaling Laws, Invariance, and Implicit Regularization](https://arxiv.org/pdf/2210.06441.pdf), Oct. 12 2022.
- [Data augmentation as feature Manipulation](https://proceedings.mlr.press/v162/shen22a/shen22a.pdf), `icml2022`.

### Data curation

- [Measuring Data](https://arxiv.org/pdf/2212.05129.pdf), Dec. 9 2022. Huggingface.
  - _"we define the task of measuring data to quantitatively characterize the composition of machine learning data and datasets"_
  - _"quantify different attributes of data along common dimensions that support comparison"_, mainly for data of vision and language'
  - _"Measuring data aids in systematically building and analyzing machine learning (ML) data towards specific goals and gaining better control of what modern ML systems will learn"_

### Dataset distillation

> Refer to [Awesome-Dataset-Distillation](https://github.com/Guang000/Awesome-Dataset-Distillation) for a list of papers colllected by Guang Li.

- [Dataset Condensation via Efficient Synthetic-Data Parameterization](https://arxiv.org/pdf/2205.14959.pdf), Jun. 2 2022. `icml2022`.
- [Efficient Dataset Distillation using Random Feature Approximation](https://arxiv.org/pdf/2210.12067.pdf), Oct. 21 2022. `nips2022`.
  - _"we demo the effectiveness of our approach on tasks involving model interpretability and privacy preservation."_
- [Dataset Distillation using Neural Feature Regression](https://arxiv.org/pdf/2206.00719.pdf), arXiv Oct. 24 2022. `nips2022`.
- [Scaling Up Dataset Distillation to ImageNet-1K with Constant Memory](https://arxiv.org/pdf/2211.10586.pdf), Nov. 19 2022.
- [A Comprehensive Survey to Dataset Distillation](https://arxiv.org/pdf/2301.05603.pdf), Jan. 13 2023.
- [Provable Data Subset Selection For Efficient Neural Network Training](https://arxiv.org/pdf/2303.05151.pdf), Mar. 9 2023.
- [Loss-Curvature Matching for Dataset Selection and Condensation](https://arxiv.org/pdf/2303.04449.pdf), Mar. 8 2023.

### Machine Unlearning

- [On the Necessity of Auditable Algorithmic Definitions for Machine Unlearning](https://arxiv.org/pdf/2110.11891.pdf), Oct. 22 2021.
- [Dataset inference: Ownership resolution in machine learning](https://arxiv.org/pdf/2104.10706.pdf), Apr. 2021 `iclr021`
- [Unrolling SGD: Understanding Factors Influencing Machine Unlearning](https://arxiv.org/pdf/2109.13398.pdf), Sep. 27 2021.

### Data Summarization

- [Data Summarization via Bilevel Optimization](https://arxiv.org/pdf/2109.12534.pdf), Sep. 2021. `knowledge tracing`


### Data Valuation

- [Rissanen Data Analysis: Examining Dataset Characteristics via Description Length](https://arxiv.org/abs/2103.03872), Feb. 2021.
- [Information-Theoretic Measures of Dataset Difficulty](https://kawine.github.io/assets/dataset_difficulty.pdf), `acl 2022` submitted.


### Data Certificate

- [Learn then Test: Calibrating Predictive Algorithms to Achieve Risk Control](https://arxiv.org/pdf/2110.01052.pdf), Oct. 2021.


### Analysis on relationship between data examples and generalization

- [A Few More Examples May Be Worth Billions of Parameters](https://arxiv.org/pdf/2110.04374.pdf), Oct. 2021.


### Data Curation for Training Foundation Model

#### Deduplication

- [Deduplicating Training Data Makes Language Models Better](https://arxiv.org/abs/2107.06499), Jul. 14 2021.
- [LSH methods for data deduplication in a Wikipedia artificial dataset](https://arxiv.org/pdf/2112.11478.pdf), Dec. 10 2021. `local sensitive hash`

#### Dataset Construction

- [A pipeline for large raw text preprocessing and model training of language models at scale](https://upcommons.upc.edu/bitstream/handle/2117/343268/155957.pdf?sequence=1), Dec. 2021 `spanish roBERTa`
